# How to Host an Online Resume Using Modern Technical Writing Tools

This README provides the steps necessary to host an online resume, and README, in a GitHub Pages Public Repository. Utilizing Markdown, a lightweight markup language, and Jekyll, a static site generator, you will be able to share and host documents on the distributed version control system, GitHub Pages.

## Summary

  - [Finished Product](#finished-product)
  - [Getting Started](#getting-started)
  - [Instructions](#instructions)
      1. [Create a repository](#create-a-repository)
      2. [Add your resume formatted in Markdown to the repository](#add-your-resume-formatted-in-markdown-to-the-repository)
      3. [Generate a static site with a theme](#generate-a-static-site-with-a-theme)
  - [More Resources](#more-resources)
  - [Authors and Acknowledgements](#authors-and-acknowledgements)
  - [FAQs](#FAQs)
  
## Finished Product
   ![Online Resume](https://github.com/sebaraneda/sebaraneda.github.io/blob/main/Demo.gif)
    
   _Figure 1: Online Resume_  

## Getting Started
You will need... 
1. A resume formatted in [Markdown](https://www.markdownguide.org/basic-syntax)
    - Markdown is a lightweight and readable markup language that allows a static site generator, Jekyll in our case, to format and present your resume while allowing you to quickly update it as needed. 
    - To start working with Markdown, you'll need an editor such as...
  
      [Visual Studio Code](https://code.visualstudio.com/) 
      
        - Simple editor with a live preview option, and if you're reading this, there's a good chance you already have it.
      
      OR
     
      [Make a README](https://www.makeareadme.com/)
      
        - Simple online Markdown editor with spell check and live preview. If you don't want to install anything and just want to get going working with Markdown, I can't recommend Make a README enough!
        
    - If you are new to Markdown, check out the Markdown Basic Guide and Markdown Tutorial in the [More Resources](#more-resources) section.
      
2. A [GitHub Account](https://github.com/join)
   
## Instructions

#### 1. Create a repository
 - Once signed into [GitHub](https://github.com/), create a new repository named `username.github.io`and make sure the repository is public.
    For example: sebaraneda.github.io
 
   ![Creating a repository](https://github.com/sebaraneda/sebaraneda.gethub.io/blob/main/Step%201.gif)
    
   _Figure 2: Creating a repository_
  
- This step relates to using distributed version control from _[Modern Technical Writing][1]_. A repository allows for documentation to stay in sync with the latest changes, while easily allowing for contribution.

#### 2. Add your Markdown formatted resume to the repository
 - From the repository home page, add your resume Markdown file. Ensure the file name is `index.md`.
 
   ![Adding files to a repository](https://github.com/sebaraneda/sebaraneda.gethub.io/blob/main/Step%202.gif)
   
   _Figure 3: Adding files to a repository_
   
 - Markdown language is readable, allowing for quick updates. This functionality, as highlighted by Etter, is important for version control, by enabling multiple versions of your resume to be updated and recorded.
   
#### 3. Generate a static site with a theme
- In the `Settings` tab, head over to the `GitHub Pages` section, click `Change theme` and select a theme. If you want to look into a custom Jekyll template, you can view a quick intro to Jekyll [here](https://www.mikedane.com/static-site-generators/jekyll/).

  ![Choosing a Jekyll theme](https://github.com/sebaraneda/sebaraneda.gethub.io/blob/main/Step%203.gif)
  
  _Figure 4: Choosing a Jekyll theme_
  
- The use of a static website is a key principle from Etter’s book. Using a static site generator, such as Jekyll, we can transform Markdown content into an appealing and themed static website.

The tools from Andrew Etter's book _[Modern Technical Writing][1]_ are as follows...

 1. Use Lightweight Markup (utilization of Markdown)
 2. Use Distributed Version Control (GitHub Pages)
 3. Make Static Websites (Static site generator, Jekyll)

[1]: <https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS> "Etter, Andrew. Modern Technical Writing. Kindle edition, Self-published, 2016."

## More Resources
 - [Markdown Basic Guide](https://www.markdownguide.org/basic-syntax)
 - [Markdown Tutorial](https://www.markdowntutorial.com/)
 - Andrew Etter's book _[Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)_
 - [GitHub Pages](https://pages.github.com/)
 - [Introduction to Jekyll](https://www.mikedane.com/static-site-generators/jekyll/)

## Authors and Acknowledgements
  - [Slate Jekyll theme for GitHub Pages](https://github.com/pages-themes/slate)
  - Thank you to my group members: Connor Gehman, Quoc Nguyen, and Jiachi Sun
  - Etter, Andrew. _[Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)_. Kindle edition, Self-published, 2016.

## FAQs
Why is Markdown better than a word processor?
 - Markdown allows documentation to be kept in version control, allows for simple separation of content and style, of HTML and CSS, and best of all, is free to use.

Why is my resume not showing up?
 - It can take up to 20 minutes for your resume to show up on GitHub Pages. If after 20 minutes, the problem still persists, ensure it is entitled `index.md`, and your branch is set to main in the GitHub Pages section of settings and the correct folder is selected.
