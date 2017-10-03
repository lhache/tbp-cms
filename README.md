# The Better Play CMS

## Instructions for pros

### Installation
- `git clone https://github.com/lhache/tbp-cms.git`

### Running the project locally
- `hugo server -D`

### Deployment
The project is automatically deployed on http://tbp-cms.netlify.com/

## Instructions for noobz

It requires you have a terminal opened and are in the folder where the code is store, 'workspace' for exemple.

### Prerequisites (MacOS)
- [homebrew](https://brew.sh/)
- [git](https://git-scm.com/download/mac)
- [yarn](https://yarnpkg.com/lang/en/docs/install/#mac-tab)
- [hugo](https://gohugo.io/getting-started/installing/#macos)

#### Clone the repo on your computer
- `git clone https://github.com/lhache/tbp-cms.git`
- `cd tbp-cms`

#### Get latest code
- `git fetch` will ask the internet of cloudz what's the latest version of the app
- `git pull` will bring that code to your computer

#### Push your code
- make sure you got the latest code
- `git status` to see all the files that have been modified
- `git add .` will select all the files you need to commit or `git add file.xx` to add a specific one
- `git commit -m "write what you did here"` will commit all the files previously selected
- `git push` will push all the committed files to the repository on the cloudz of the internetz

If you're not sure or if something strange prevents you from pushing code, ask a pro.

## Writing new content pages
- the content is written in markdown, you can read instruction [here](https://guides.github.com/features/mastering-markdown/) or   [there](https://daringfireball.net/projects/markdown/syntax#precode)
- the available folders for your content are in the 'content' folder
- *warning* make sure the new files ends by ".md"
- create a new landing page => `hugo new landing/xxxxxxxx.md`
- create a new content page => `hugo new company/xxxxxxxx.md`
- *warning* make sure the new files have a "front-matter", something that looks more or less like
 <pre><code>
 ---
title: "Test"
date: 2017-09-14T18:35:24+02:00
draft: false
---
 </code></pre>
