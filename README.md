# Shimin233.github.io
Welcome to my [Github page](https://shimin233.github.io) :D

## Questions
### Display markdown files on Githubpages using Jekyll - \_config.yml
[Guide](https://nicolas-van.github.io/easy-markdown-to-github-pages/). I have to figure out how to apply .yml if I start with a repository without any
configuration file.
----update-----------
i did it! :D The steps are as below:
1. use any text tool to type
 ```
 plugins:
  - jekyll-relative-links
relative_links:
  enabled: true
  collections: true
future: true
include:
  - CONTRIBUTING.md
  - README.md
  - LICENSE.md
  - COPYING.md
  - CODE_OF_CONDUCT.md
  - CONTRIBUTING.md
  - ISSUE_TEMPLATE.md
  - PULL_REQUEST_TEMPLATE.md
  - JobScraping.md
 ```
 where I think those .md files are completely up to what .md files you want to show - but I did not delete any from the [guide](https://nicolas-van.github.io/easy-markdown-to-github-pages/) just for safety. Then just save it with name `_config.yml' to your personal webpage .github.io repository folder. Yes, just type it and save, yout computer will recognise how to use it for your webpage (for example, my mac opens it with Visual Studio code by default ;P)
2. Quote the .md file, by simply replacing the `.md` extension by `.html`, in your index.html; the format `<a href=""></a>` is just like quoting another html, images and pdfs in html. Your jekyll and \_congif.yml will then recognise that you want to display this .md in the form of a html webpage. My codes are like:
```html
<p class="sans-serif"> I am simultaneously trying to apply what I learned to real needs, such as 
      <a href="JobScraping.html">Webscraping for job descriptions</a> </p> <!--JobScrapingmd is in the same folder as index.html-->
```
3. Done! Click `Webscraping for job descriptions` on the page, it will lead to a clean html-like dispaly of your .md file. 

### MkDocs - to be used to Github pages formatting 2
[Materials for MkDocs](https://squidfunk.github.io/mkdocs-material/)

### Add author / copyright info to the image I drew

### The update the resulting webpage has a delay
Maybe I need to set the correct timezone, see [this suggestion](https://stackoverflow.com/a/35388975)

### Add texts above image
see [guide](https://www.w3schools.com/howto/howto_css_image_text.asp)

### Rotation not successful in Safari
see [suggestion](https://stackoverflow.com/questions/44316184/transform-rotate-doesnt-work-in-safari)

### Cut and resize image at the same time
[multiple solutions here](https://stackoverflow.com/questions/493296/css-display-an-image-resized-and-cropped); 
if want to resize to the screen size, check [this](https://stackoverflow.com/questions/4684304/how-can-i-resize-an-image-dynamically-with-css-as-the-browser-width-height-chang)

### How enable efficient whole-website keyword search?
to simplify review and summary of previous notes/ideas; also enable multi-task viewing, like across-notes

### Timeline structure of contents shown explicitly?
to clearly show my learning/career paths



## Potential projects to put
### Job scraping

#### Good example to learn from
Thanks to https://yang-xijie.github.io, I got inspired by structures and contents

### My learning and notes
links to my Github repositories

### Languages, hobbies, etc
Mandarin, English, French (basic)\
Music: Erhu\
Others: Jazz Dance, FIgure skating, Manga drawing

### Those in cover letter
zoom meeting in 2020-21 winter; tutoring and volunteer experience; (video channel); 

### CFA I

### Coursera 
[Python and web scrapping](https://www.coursera.org/learn/python-project-for-data-science/home/week/1)
 there is a 6-month extension to the IBM cloud trial account, while the IBM cloud account is necessary to create the final result of the final project of week 1; decide carefully when to start the trial + this extension. \
[Prerequisite](https://www.coursera.org/learn/python-for-applied-data-science-ai/lecture/W6xwd/rest-apis-http-requests-part-1)


### Data analysis
mindmaps, summaries

### Insights and ideas into certain topics
the difference between subjects with experiments and surveys in real word, and those only need pen&paper(pure maths except part of stats; theoretic physics?): collect facts from real world and trace back to study the underlying mechanism (e.g. empirical stats in finance like empirical duration), while the latter ones build mechanism and structure of theory to lead to results in real word (e.g. cannot invent an unknown maths theorem)

### Leetcode/Quant interview: any project?
