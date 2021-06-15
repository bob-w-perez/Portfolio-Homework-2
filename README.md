# Portfolio-Homework-2


- This project was a refactoring of a marketing agencies webpage to clean up the CSS code and apply semantic standards to the HTML tags.
## Installation

go to [https://github.com/bob-w-perez/Code-Refactor-Homework-01](https://github.com/bob-w-perez/Code-Refactor-Homework-01) to view the files and read about the changes

## Usage
![screenshot](https://github.com/bob-w-perez/Code-Refactor-Homework-01/blob/main/assets/images/screenshot.jpg "Screenshot")

go to [https://bob-w-perez.github.io/Code-Refactor-Homework-01/](https://bob-w-perez.github.io/Code-Refactor-Homework-01/) for the live webpage

* BONUS: go to [https://bob-w-perez.github.io/Homework-01-flex/](https://bob-w-perez.github.io/Homework-01-flex/) for a version where scaling issues are fixed


## Changes Made
-- Changes made to index.html

----- replaced generic 'div' tags with more descriptive alternatives such as 'main', 'aside',
      'nav', 'header', etc.

----- by giving these elements distinct tags, many of their classes were made irrelevant and
      were therefore removed

----- a broken link in the navbar was fixed by adding an 'id' attribute to its target element

----- 'alt' attributes were added to all of the pages images, except for the hero image which
      was tagged as a figure to preserve its corresponding CSS declaration

----- unnecessary 'class' attributes were removed from the images, these classes only refered
      to single elements and were redundant for the webpage's functionality

----- a descriptive title and heart-shaped favicon were added to the browser tab

----- the 'seo' in the Horiseon page heading were a different color to highlight the S.E.O
      aspects of the company, but the difference was barely noticeable so the color was changed
      to highlight it better


-- Changes made to style.css

----- class selectors that were no longer necessary due to the new element tags in the HTML
      were replaced by the corresponding element selector

----- some declarations had nested selectors that were unnecessarily long were shortened, the
      elements these referred to only occured in one parent element so the extra specificity
      was discarded in favor of conciseness while preserving functionality

----- the order of some declarations were changed so that the order of the CSS page reflected
      the same order as their corresponding HTML elements

----- each element of the same type in the 'main' and 'aside' sections had the same CSS parameters,
      so the CSS declarations were consolidated to improve readability and make the code neater



## Contributing
Solo project for GATech Coding Bootcamp

## License
MIT License

Copyright (c) 2021 Robert Perez

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