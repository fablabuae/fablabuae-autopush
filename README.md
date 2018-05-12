# fablabuae-autopush

## Introduction

**fablabuae-autopush** is an automatic documentation script created by [Hashim Al Sakkaf](https://github.com/HashimNabil) for [fabacademy](http://fabacademy.org/) that is based on [Markdown](https://en.wikipedia.org/wiki/Markdown). This script is customized for [ Massimo Menichinelli](https://github.com/openp2pdesign/FabAcademy_Template) fabacademy template any template but can be easily customized for any bootstrap template.

The script will automate the documentation process by:  
- Checking the folder size.
- Convert Markdown pages to HTML using pandoc
- Finally, pulling, adding files, commiting and pushing to the archive

## Requirements

- install [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [pandoc](https://pandoc.org/installing.html).
- Put your fabacademy repo in Desktop (This applies for all operating systems)

## Usage

- To use this script, first clone fablabuae-autopush repo from [here](https://github.com/fablabuae/fablabuae-autopush).
- Then, copy everything inside fablabuae-autopush and paste it inside the Desktop folder.  
Now you are almost ready to use it, but first edit on the template and customize it according to your choice.
- Now to use it all you have to do is open a terminal at the location you saved the script (Desktop in this case) and write:

```push your commit message is here```  

where "push" is the script name

## Notes

- The assignments folder are named "weekX" where X is the assignment week number, because the script is having a "for" loop so will be easy to convert all the markdown files for all the week with few lines of code only! This name will be used at the backend of your website, and you can name the weeks in the "excercises-menu.html" html file.
- Menu bar and back button are still to be added at each page soon in the future.

## Credits

- Used CSS styling for the weekly pages is [normalize.css v2.1.3](https://github.com/stevenmiller888/mindjs.net/blob/master/components/necolas-normalize.css%40v2.1.3/normalize.css)
