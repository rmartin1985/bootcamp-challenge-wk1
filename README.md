# Hori*seo*n homepage: Code Refactor Challenge week 1

## Description

For this task I was assigned the goal of making the Hori*seo*n Homepage website meet accessibility standards. I was also tasked with refactoring the legacy code base in both the HTML and CSS to make sure that everything was working properly and to clean up the code for any duplicate or unneccesary code. 

I was provided the starter code from the company and noticed right away that the index.html file was structered well, but it was lacking in symentic HTML language that would help instantly to make this site more accessible. I went through the document and changed non-semantic elements such as `<div>` and `<span>` to more semeantic elements such as `<header>`, `<footer>`, and `<aside>`.

The next steps were to go through the code and add notes where applicable to break down the code in to more manageable sections for easier reference in the future if more updates or refactoring are needed. 

All of the images were missing `<alt>` titles as well. These will go a long way to aiding in accesibility for those using screen readers to be able to describe what the image represents. I added those to all of the images that needed to be described using a screen reader. 

When it came to refactoring the stylesheet, there were quite a few areas where the same exact code was written for mulitple parent and child elements. Instead of having them written out multiple times, I consolodated each of them in to one class and then was able to keep one set of code to style all of the elements at once. 

Lastly, I made sure that the links in the navigation section of the header element were all working correctly by linking the correct ids in the index.html to their respective sections. Also was able to make sure the font-style of the *seo* in the logo matched the markup while still being emphaised per the company's request. 

You can see the finished webpage deployed here: [Horiseon Homepage](https://rmartin1985.github.io/bootcamp-challenge-wk1/)

![Horiseon](https://media.giphy.com/media/9D5JkjNRojSHZ9PBjL/source.mov)

![Horiseon](./Develop/assets/images/Horiseon-screenshot.jpg)

## License

MIT License

Copyright (c) [2021] [Richard-Martin]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.