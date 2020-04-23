## [Environment Setup](#environment-setup) 

1. Make sure installed hugo is to install/update hugo extended, minimal
 version 0.68.3 and above by checking `hugo version`
1. If not, download and install `hugo_extended_0.69.0_{OS}-{XX}bit` from the
 [Hugo releases](https://github.com/gohugoio/hugo/releases)
1. Clone the [ual.sg repository](#)
1. Cd into the root of the repository folder, sync the [hugo-academic](https://github.com/gcushen/hugo-academic) submodule theme by typing `git submodule update --init --recursive`
1. Run `hugo -D -F server --disableFastRender` to build and serve the website
 from source
1. Check website at [localhost:1313](http://localhost:1313/)


## [Development Dos and Don'ts](#development-dos-and-donts)

### Dos

1. Refer to [Hugo documentation](https://gohugo.io/documentation/) to get
 a basic understanding of archetypes
, taxonomies, and content management
1. Refer to [Academic Framework documentation](https://sourcethemes.com/academic/docs/) on modifications and customization to the theme
1. Refer to [Hugo commands](https://gohugo.io/commands/) to learn how to add
 new content and configure the website 
1. Follow the [development workflow](#development-workflow) below
1. When creating new blog posts, follow the title, structure and other things from previous blog posts (check `content/post`).
1. Set `draft: true` in the header of content you don't want to have published at this point.
1. Remember to include any images, external files that is relevant to the
 content being added, for some may have a global `.gitignore` that prevents
  detection of those files
1. Make sure to always check for updates from the master branch for merged
 changes, `git checkout master && git pull origin master`

### Don'ts

1. Do not modify the original themes in `themes/academic` folder. Follow the
 original hugo directory structure to make amendments to existing themes
1. Do not check-in `public` and `resources` to the git repository


### Additional notes:

1. If you want to deploy your local server online (e.g. for others to check as a provisional solution), have a look at `ngrok`.
1. Importing our publications is a bit tricky, the process will be simplified
 in the future. In short, update the `publications.bib` file and then run `academic import --bibtex publications.bib`


## [Development Workflow](#development-workflow)

1. Make sure to always check for updates from the master branch for merged
 changes, `git checkout master && git pull origin master`
1. When ready to start making changes, make sure to create a new git branch
 by `git checkout -b {branch-name}`
1. Constantly save and preserve work in progress by committing to the branch and
 push to github `git push origin {branch-name}`
1. When content is ready for review, create a pull request of the branch to
 be merged to `master`
