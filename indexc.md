[Data Management Implementation Plan Template](datastorage-norm-edited.md)  
[Data Management Implementation Guidance Document](guidance-edit.md)  
[Github Repository](https://github.com/landonma/datamanagement)  

# How to Use This Repository
This repository contains the tools necessary to create a data management implementation plan and a webpage for your project. We have created template and guidance documents to allow you to easily create a plan specific for your project. as a lot of this walkthrough is designed to help set up a Github Pages webpage. The following steps contain links and instructions to help you through this process. After completing these steps you will have a data management plan and a working webpage for specific to your research project. If you are only interested in creating the data management plan and don't want to make a Github Webpage then skip to [this](#using-our-template-and-guide-documents) step.


## What is a Data Management Implementation Plan

## What is Github Pages
* Once a repository is set up with Github pages, [any](https://landonma.github.io/datamanagement/osulogo.jpg) file in the repository can be navigated to in a web browser. Markdown or html files will be viewed as webpages
* **ALL** repositories linked with the user who set up Pages will become navigable with Github Pages

## Set Up A Github Repository
Github is a website used to share data and allow multiple people to work on the same project. You will need a Github account in order to complete this guide and can create one [here](hhttps://github.com/join "Create a Github account").  
* Note: the url for the webpage will use either the username or organization name which sets it up. Try to make sure the URL will be appropriate to share with others and relevant to what is on the webpage.

There are two types of repositories on GitHub; public ones and private ones. Public repositories can be seen by and downloaded by anyone on the web but only edited by collaborators. Private repositories can only be seen by its contributors.  Normally Github charges for private repositories but researchers can apply for a free private account by following [these](https://help.github.com/articles/applying-for-an-academic-research-discount/ "Apply for an Free Private Academic Research Account") steps.  
###### ** IMPORTANT NOTE **
GitHub Pages are **ALWAYS PUBLIC REGARDLESS OF THE PRIVACY OF THE REPOSITORY**. This combined with the fact that **ALL REPOSITRIES** and **ALL FILES** are set up with pages for a uses means you must be certain their is **ABSOLUTELY ZERO** private information linked with your account before you set it up with Github Pages. If there is some question about whether this holds true for your or not, it maybe best to simply create a new Github account.

Next you will need to create a new repository set up with Github pages by following the steps provided [here](https://pages.github.com/ "Github Pages").  
* Note: Github pages does take some time to respond to new pages and edits so wait 3-5 minutes after making changes before assuming something went wrong
* Once a user or organization is set up to use Github pages, all their repositories will be navigable in a browser  

Next clone or download [our repository](https://github.com/landonma/datamanagement "Data Management Implementation Plan Repository"). Then place upload the template file into your own repository. ([Here](https://help.github.com/articles/adding-a-file-to-a-repository/ "Adding a File to a Repository") is a quick article if you are unfamiliar with Github)

## Markdown editing
Markdown was created to be easy to read and edit and we use this format for all the documents in this repository. Markdown files(.md) have some of the functionality of writing documents in an HTML format while still remaining easily readable. Github and Github Pages are set up to use Markdown already. The coding involved with formatting a Markdown document is easy to learn and you can find a guide for using markdown [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown Cheatsheet"). Some additional tips for creating markdown documents:
* There must be a space after the ##'s when making headers
* There is NO space when bolding and using italics; ie. **bold** not ** bold **
* If you want to force a line break put two spaces at the end of the line then press Enter.
(ie. end of line." __ ")
* The guide shows the different ways to format hyperlinks but doesn't describe the different types of links. I describe the different links in other section [below](#customizing-github-pages).

It is easiest to edit markdown files either by editing the documents through Github in a web browser or by using source code editing software such as Notepad++ or Atom (these docs were created using Atom). You could theoretically use Microsoft Word or Google Docs but it is strongly recommended that you use Github's editor instead. To edit them using Github simply navigate to your repository, click on the file you want to edit and click the edit (pencil) button on the top right of the page.

## Using Our Template and Guide Documents
The template markdown file (found [here](datastorage-norm-edited.md)) is meant to be edited and filled out directly. As you look through the template file you should fill in any _____ spaces and change any of the boiler-plate text with details specific for your project.  



The guidance document (found [here](guidance-edit.md)) is meant to help you think about the important parts of each section and is **not** meant to be edited and published. This document will help illustrate what is important to include and consider in each section.

## Customizing Github Pages
When you use Github Pages your repository is your webserver. Therefor, the file titled "index" will be the homepage of your website. For the repository we created that page is the one you are reading right now. For your repository you will want something that suites your needs.

If the only page you want is the data management implementation plan document you can rename that document "index.md". Now whenever you navigate to your repository URL you will get document.    
You may want a list of links with some basic text for the home page. To do this, use this markdown file as a template and edit the text and links as necessary. There are three types of links used in this repository and they all have slightly different text inside the parentheses " () ". To best distinguish between these types it is best to look at the code in an editor.

* Some of them are basic hyper links which contain the full url of the page in the () which is linked to ie. [google.com](google.com).
* Others are relative links which match a file name in your repository. To create this type of link include the full file name exactly as it appears in the repositry including the extension. [Data Management Implementation Plan Template](datastorage-norm-edited.md). All the links that point to other pages in this repository were created using relative links so if you have all the file names as this repository then your wont have to change any of these links (but may need to delete ones such as the link to the guidance file).
* There are also "links" which jump to header within the same page. These are used in the table of contents [this](#customizing-github-pages). The link must be all lower case and the spaces are replaces with dashes -. Make sure to change these links whenever a header name is changed. Also note that there should only be **ONE #** regardless of the header level.


Github has also created a number of themes that change the appearance of your pages and can be viewed [here](http://jekyllthemes.org/ "Available Themes").  Instructions on how to apply the themes are [here](https://help.github.com/articles/adding-a-jekyll-theme-to-your-github-pages-site/ "Add Jekyll Themes"). This repository has **no theme** applied to it but you are welcome to try them out.
* I suggest the method that edits the "_ config" file because you can simply delete the line if you want to remove the theme later.

You can also use HTML to create/format any pages on your repository. For simplicity and to show what Markdown can do; nothing in this repository was written using HTML.
