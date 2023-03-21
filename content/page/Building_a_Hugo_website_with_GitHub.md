---
title: "Projects"
date: 2023-03-05T23:37:36-08:00
author: "Miles Wallace"
description: "Building a Hugo Website with GitHub"
tags: ["Hugo", "GitHub", "Hugo website"]
#cover:
    #image: img/raspberry_pi.png
    #alt: 'This is a post image'
    #caption: 'This is the caption'
---
## "Building a Hugo Website with GitHub."
#### _03/05/2023_  
____
Hugo is one of the fundamental static site generators to install because it’s distributed as a single binary.

1. Install Hugo on your local machine. You can download the latest version of Hugo from the official website: https://gohugo.io/getting-started/installing/.

2. Create a new Hugo site using the command line interface by typing the following command in your terminal or command prompt:

hugo new site your-site-name

This will create a new Hugo site in a folder named your-site-name.

3. Choose a theme for your website from the Hugo theme gallery: https://themes.gohugo.io/. You can select a theme by navigating to the theme directory, copying the theme URL, and then adding it to your Hugo site's config.toml file. For example, to use the "Ananke" theme, add the following line to your config.toml file:

theme = "https://github.com/budparr/gohugo-theme-ananke.git"

4. Create your website's content by adding Markdown files to the content/ directory of your Hugo site. For example, you could create a new blog post by typing the following command:

hugo new posts/my-first-post.md

5. Preview your website by running a local development server with the following command:

hugo server -D

This will generate your website and launch a local server at http://localhost:1313/.

6. Initialize a new Git repository in your Hugo site's root directory by running the following commands:

cd your-site-name
git init
git add .
git commit -m "Initial commit"

7. Create a new repository on GitHub by navigating to https://github.com/new and following the prompts to create a new repository. Note the repository's URL.

8. Add the GitHub repository as a remote to your local Git repository by running the following command:

git remote add origin https://github.com/your-username/your-repository-name.git

9. Push your local Git repository to GitHub by running the following command:

git push -u origin master

10. Configure GitHub Pages to serve your website by going to your repository's settings page, scrolling down to the "GitHub Pages" section, and selecting "master branch" as your source. Your website should now be hosted at https://your-username.github.io/your-repository-name/.