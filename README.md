## [Environment Setup](#environment-setup) 

1. Refer to `go.mod` for the current wowchemy version in this repository.
1. Refer to the wowchemy release notes for hugo-wowchemy version compatibility. 
1. Make sure installed hugo is the extended version and is compatible with wowchemy theme current release. 
1. Check previously installed hugo version by `hugo version`. 
1. If needed, download and install/upgrade the compatible hugo from the  [Hugo releases](https://github.com/gohugoio/hugo/releases)
1. Clone the [ual.sg repository](#)
1. Cd into the root of the repository folder, run `git checkout master && git pull origin master` to sync the latest content from master branch.
1. Run `hugo -D -F server --disableFastRender` to build and serve the website from the local source. 
1. Check website at [localhost:1313](http://localhost:1313/). Fix error from previous step, if any, before proceeding any further. 



## [Development Dos and Don'ts](#development-dos-and-donts)

### Dos

1. Refer to [Hugo documentation](https://gohugo.io/documentation/) to get a basic understanding of archetypes, taxonomies, and content management
1. Refer to [Wowchemy documentation](https://wowchemy.com/docs/) on modifications and customization to the theme
1. Refer to [Hugo commands](https://gohugo.io/commands/) to learn how to add new content and configure the website 
1. Follow the [development workflow](#development-workflow) below
1. When creating new blog posts, follow the title, structure and other things from previous blog posts (check `content/post`).
1. Set `draft: true` in the header of content you don't want to have published at this point.
1. Remember to include any images, external files that is relevant to the content being added, for some may have a global `.gitignore` that prevents detection of those files
1. Make sure to always check for updates from the master branch for merged changes, `git checkout master && git pull origin master`

### Don'ts

1. Do not check-in `public` and `resources` to the git repository


### Additional notes:

1. Importing our publications is a bit tricky, the process will be simplified
 in the future. In short, update the `data/publications.bib` file and then run `academic import --bibtex publications.bib`. Install academic by with Pip or other python package manager, ie. `pip3 install -U academic`. Futher details refer to [Publications section](https://wowchemy.com/docs/content/publications/). 


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

Other Useful Resources:
- [Git and GitHub Tutorial](https://www.freecodecamp.org/news/git-and-github-for-beginners/)
- [Netlify with GitHub](https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/)
- [Netlify Documentations](https://docs.netlify.com/)
