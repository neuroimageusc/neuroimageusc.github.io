## Getting started
1. Create a new repository for your project/software
1. Use git to clone the repository to local
1. Copy the everything inside template to your local repository except for
	* .git
	* .sass-cache
	* \_site
1. Find **_config.yml** and edit
    * **title**: your project name
    * **author name**: your name
    * **baseurl**: the GitHub repository name, has to be exactly match and note the leading slash there
1. All pages are stored under **_pages** folder.
1. Corresponding navigation items on the top are stored in **_data** -> **navigation.yml**
1. Bib files and PDF files for your paper should be put inside **files** folder
1. Illustrative images/pictures should be put inside **images** folder
1. After making changes, commit to local repository and push to remote

## New to Markdown language?
Here are some quick start/cheatsheet:
* [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)

Some of the features may not work on GitHub. Just try and see.

## How to test your website locally?
1. Clone your repository to local
1. Make sure you have [jekyll](https://jekyllrb.com/) installed
1. Run `jekyll serve --baseurl ''` inside your local repository
1. Open your browser and point it to [http://localhost:4000](http://localhost:4000)