# <Horiseon-Refactored>

## Description

**Why?**

This project was initiated to learn about refactoring an existing built code with visibly working for most (computer) users. However the exisiting code does not flow well semantically and thus, is rather inaccessible to some users. 

**Improvements**

The refactored version will improve upon making it more accessible with the use of semantic tags and apprioriately sectioned. This will not only help others to understand the source code, but also allows search engines and accessbility tools (Screen readers, etc.) to work better.

**Acquired Knowledge**

Throughout this small project I have learnt the importance of avoiding ambuiguity when possible, and what apprioriate element tags to replace them with. I have also understood the importance of making web-development. 

I made an attempt to make it mobile-friendly, with little success. However due to my limited knowledge and time constrains, this issue is yet to be fixed. Due to this, the current version is only built for large screens (eg. Monitors). 


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Features](#features)

## Usage

By default, the files (html) included are to be viewed using a web browser such as Chrome/Safari/Mozilla, etc. 

![](develop/assets/images/Horiseon_content.png)
   

The html (and css) can also be viewed using a browser's devtools with the inspect button
Instructions: (Chrome)
1. Open Refactored_Horiseon.html using a browser (Chrome)
2. On the web browser, right-click (default setting) on your mouse
3. Move the cursor to the "Inspect" and click to view code on the browser's devtool.

![](develop/assets/images/Horiseon_inspect.png)

Another way is to open any of these files is with a code editor tool (eg. VSCode). 
VSCode can be downloaded under this link https://code.visualstudio.com/download .
Files can be opened with the code editor [(Ctrl-O) for individual files], [(Ctrl-O-K) for folders]. 

## Credits

- https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide
- https://github.com/othneildrew/Best-README-Template/blob/master/BLANK_README.md
-https://www.w3schools.com/css/css_rwd_viewport.asp
-https://www.w3schools.com/html/html_accessibility.asp
- https://www.markdownguide.org/cheat-sheet/
- https://choosealicense.com/
- https://medium.com/@justynagolawska/how-to-easily-add-screenshots-into-your-readme-file-on-github-d806a01d6ffd
-https://favicon.io/favicon-generator/

## License

MIT License

Copyright (c) [2022] [Samuel Wai Weng Yong]

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


## Features

- Semantic elements implemented (Header, body, nav, etc)
- Search engines are now able to pull the main content with the "main" element tag, and avoids pulling from the "aside" tag.
- ❤️ is complemented with the "love" description made invisible to the user, but useful for screen readers. 


