# How to Host an Online Resume Using Modern Technical Writing Tools

This README will give you the steps to host an online resume and README on a GitHub Pages Public Repository using Markdown, a lightweight markup language, with Jekyll, static site generator to share and host documents on a distributed version control system, GitHub Pages.

## Summary

  - [Getting Started](#getting-started)
  - [Instructions](#instructions)
      1. [Create a repository](#create-a-repository)
      2. [Add your resume formatted in Markdown to the repository](#add-your-resume-formatted-in-markdown-to-the-repository)
      3. [Generate a static site with a theme](#generate-a-static-site-with-a-theme)
  - [More Resources](#more-resources)
  - [Authors and Acknowledgements](#authors-and-acknowledgements)
  - [FAQ's](#FAQ's)

## Getting Started
You will need... 
1. A resume formatted in [Markdown](https://www.markdownguide.org/basic-syntax)
2. A [GitHub Account](https://github.com/join)

## Instructions

1. Create a repository
 - Once signed into [GitHub](https://github.com/), create a new repository named _username_.github.io and make sure the repository is public.
  ![](https://github.com/sebaraneda/sebaraneda.gethub.io/blob/main/Step%201.gif)
 - This step relates to using distributed version control from _[Modern Technical Writing][1]_. A repository allows for documentation to stay in sync with the latest changes while easily allowing for contribution.

2. Add your resume formatted in Markdown to the repository
 - From the repository home page, add your resume Markdown file. Ensure the file name is **index.md**
   ![](https://github.com/sebaraneda/sebaraneda.gethub.io/blob/main/Step%202.gif)
3. Generate a static site with a theme
- In the settings tab, head over to the GitHub Pages section, click _Change theme_ and select one that best suites you. If you want to look into a custom Jekyll template, you can view a quick intro to Jekyll [here](https://www.mikedane.com/static-site-generators/jekyll/).
  ![](https://github.com/sebaraneda/sebaraneda.gethub.io/blob/main/Step%203.gif)
- This step relates to making a static website from _[Modern Technical Writing][1]_. As GitHub pages allows us to host our resume on a static site using with a Jekyll theme to create a nice static website page for your resume.

The tools from Andrew Etter's book _[Modern Technical Writing][1]_ are as follows...

 1. Use Lightweight Markup (utilization of Markdown)
 2. Use Distributed Version Control (GitHub Pages)
 3. Make Static Websites (Static site generator, Jekyll)
 4. Rsync (new files get added, existing files get updated (if necessary), and old files get deleted). (GitHub repository)

[1]: <https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS> "Etter, Andrew. Modern Technical Writing. Kindle edition, Self-published, 2016."

## More Resources
 - [Markdown Basic Guide](https://www.markdownguide.org/basic-syntax)
 - [Markdown tutorial](https://www.markdowntutorial.com/)
 - Andrew Etter's book _[Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)_
 - [GitHub Pages](https://pages.github.com/)
 - [Introduction to Jekyll](https://www.mikedane.com/static-site-generators/jekyll/)

## Authors and Acknowledgements
  - [Slate Jekyll theme for GitHub Pages](https://github.com/pages-themes/slate)
  - Thank you to my group members: Connor Gehman, Quoc Nguyen, and Jiachi Sun
  - Etter, Andrew. _[Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)_. Kindle edition, Self-published, 2016.

## FAQ's
Why is Markdown better than a word processor?
 - Markdown allows documentation to be kept in version control, allows for simple separation of content and style, of HTML and CSS, and best of all, is free to use.

Why is my resume not showing up?
 - It can take up to 20 minutes for your resume to show up on GitHub Pages. If after 20 minutes, the problem still persists, ensure it is entitled "index.md", and your branch is set to main in the GitHub Pages section of settings and the correct folder is selected.
