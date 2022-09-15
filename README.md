## [Environment Setup](#environment-setup) 

1. Refer to `go.mod` for the current wowchemy version in this repository.
2. Refer to the wowchemy release notes for its compatible hugo-extended version. 
3. Installed the compatible hugo-extended version. 
4. Note for MacOS users: 
   1. the compatible hugo version is very often a few versions behind of the latest available on Homebrew. While the 
      later version very often works, it is strongly advisable to start with the specific version 
      on wowchemy Release note. 
   2. To look for the previous releases of hugo on homebrew, look for [previous 
      commits on the homebrew-core repository](https://github.com/Homebrew/homebrew-core/search?q=hugo&type=commits) to download the relevant `hugo.rb`. 
   3. Run `brew install hugo.rb` to install the specific older version of hugo. 
   4. Check the installed hugo version by `hugo version`.
6. Clone the [ual.sg repository](#)
7. Cd into the root of the repository folder, run `git checkout master && git pull origin master` to sync the latest content from master branch.
8. Run `hugo -D -F server --disableFastRender --forceSyncStatic --gc --ignoreCache 
   --panicOnWarning --printPathWarnings --printUnusedTemplates --watch` to build and serve the 
   website from the local source. All these flags are to ensure to build from changes and not 
   serving from cache. 
9. Check website at [localhost:1313](http://localhost:1313/). Fix error from previous step, if any, before proceeding any further. 


## [Development Workflow](#development-workflow)

1. Clone the [ual.sg repository](#)
1. Cd into the root of the repository folder, run `git checkout master && git pull origin master` to sync the latest content from master branch.
1. Run `hugo -D -F server --disableFastRender` to build and serve the website from local source
1. Check website at [localhost:1313](http://localhost:1313/)
1. When ready to start making changes, make sure to create a new git branch by `git checkout -b {new-branch-name}`
1. Constantly save and preserve work in progress by committing to the branch and push to github `git push origin {new-branch-name}`.
1. Create a pull request and wait for conflict checks to complete. Netlify will provide a link to preview the website in progress.  
1. Make any other necessary changes, review the preview site until it's satisfactory. 
1. When content is ready to be published publicly, merge the pull request to `master` branch. 
1. Wait for Netlify to publish to the production site, and check for new content. 

## [Development Dos and Don'ts](#development-dos-and-donts)

### Dos

1. Refer to [Hugo documentation](https://gohugo.io/documentation/) to get a basic understanding of archetypes, taxonomies, and content management
2. Refer to [Wowchemy documentation](https://wowchemy.com/docs/) on modifications and customization to the theme
3. Refer to [Hugo commands](https://gohugo.io/commands/) to learn how to add new content and configure the website 
4. Follow the [development workflow](#development-workflow) below
5. When creating new blog posts, follow the title, structure and other things from previous blog posts (check `content/post`).
6. Set `draft: true` in the header of content you don't want to have published at this point.
7. Remember to include any images, external files that is relevant to the content being added, for some may have a global `.gitignore` that prevents detection of those files
8. Make sure to always check for updates from the master branch for merged changes, `git checkout master && git pull origin master`
9. Any customizations of styles shall be made by additing the style specifications to the 
   `assets/scss/custom.scss` file.

### Don'ts

- DO NOT check-in `public` and `resources` to the git repository
- DO NOT modify the other original stylesheets in `assets/scss/`. You'd thank youself when performing wowchemy updates in the future. 

## [Additional notes](#additional-notes)

### Importing Bibtext

Importing our publications is a bit tricky, the process will be simplified
 in the future. In short, update the `data/publications.bib` file and then run `academic import --bibtex publications.bib`. Install academic by with Pip or other python package manager, ie. `pip3 install -U academic`. Futher details refer to [Publications section](https://wowchemy.com/docs/content/publications/). 

### Updating Wowchemy
The update wowchemy with newer releases must be performed on each newer release, chronologically 
from older to newest. For example, to update from v5.2.0 to v5.5.0, one must update in these 
sequences: v5.2.0 -> v.5.3.0, v5.3.0 -> v5.4.0 and finally v5.4.0 to v5.5.0. 

There are two path options to perform updates.  

#### Option 1: 
1. Clone the latest content from this [ual.sg repository](https://github.com/ualsg/ualsg.netlify.app), as local dev folder. 
2. Make a copy of the clone from above, as local ref folder (to refer to current settings 
   configurations and content from).
3. Clone the next release of [wowchemy repository](https://github.com/wowchemy/wowchemy-hugo-themes).
4. Copy the content of archetypes, assets, config, content, data, layout from the new release 
      of wowchemy to local dev folder
5. Expect and fix any build errors, build site, review changes and make necessary adjustments
6. Any styles from previous releases that wants to be retained should be moved to the 
   `assets/scss/custom.scss` file.

#### Option 2:
1. Clone the next release of [wowchemy repository](https://github.com/wowchemy/wowchemy-hugo-themes). 
2. Copy the content [`starters/academic`](https://github.com/wowchemy/wowchemy-hugo-themes/tree/main/starters/academic) to a new local dev folder. 
3. Clone the latest content from this [ual.sg repository](https://github.com/ualsg/ualsg.netlify.app) as local ref folder. 
4. Copy the configurations and content from local ref folder to local dev folder. 
5. Expect and fix any build errors, build site, review changes and make necessary adjustments
6. Any styles from previous releases that wants to be retained should be moved to the 
   `assets/scss/custom.scss` file.

### Other Useful Resources:
- [Git and GitHub Tutorial](https://www.freecodecamp.org/news/git-and-github-for-beginners/)
- [Netlify with GitHub](https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/)
- [Netlify Documentations](https://docs.netlify.com/)
