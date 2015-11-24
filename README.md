# WebStorm Templates

A collection of live and file templates for JetBrains WebStorm >= 10

## Table of Contents

  1. [Motivation](#motivation)
  1. [Installation](#installation)
  1. [Abbreviations](#abbreviations)
  1. [Contributing](#contributing)
  1. [License](#license)

## Motivation

The angular-styleguide templates were adapted for the [johnpapa/angular-styleguide repo](https://github.com/johnpapa/angular-styleguide) in response to [issue #529] (https://github.com/johnpapa/angular-styleguide/issues/529). 

## Installation

  - Live Templates    
    - Download the [webstorm-angular-live-templates.xml](https://raw.githubusercontent.com/MAustinMMDP/webstorm-live-templates/master/angular-styleguide/webstorm-angular-live-templates/webstorm-angular-live-templates.xml) file
    - Place the file in your WebStorm [templates](https://www.jetbrains.com/webstorm/help/project-and-ide-settings.html) folder
    - Open WebStorm or, if already open, Synchronize your settings with `CTRL`+`ALT`+`Y`
    - Skip to the [abbreviations](#abbreviations) section
      
    *Individual live templates are also available for download within the [webstorm-angular-live-templates](angular-styleguide/webstorm-angular-live-templates) folder*
    
  
  - File Templates
    - Download the contents of the [webstorm-angular-file-templates](angular-styleguide/webstorm-angular-file-templates) folder
    - Place it in your [fileTemplates](https://www.jetbrains.com/webstorm/help/project-and-ide-settings.html) folder
    - Restart WebStorm
    - Press `ALT`+`Insert` to open the 'New' pop-up menu and select the template
  
**[Back to top](#table-of-contents)**    
    
## Abbreviations

To use the new live templates simply open a new JavaScript file and type the following abbreviations followed by a `TAB`:

    ```javascript
    // These are full file snippets containing an IIFE
    ngapp     // creates an Angular module setter
    ngcontroller // creates an Angular controller
    ngdirective  // creates an Angular directive
    ngfactory    // creates an Angular factory
    ngfilter     // creates an Angular filter
    ngservice    // creates an Angular service    
    
    // These are partial snippets intended to be chained
    ngconfig     // defines a configuration phase function
    ngmodule     // creates an Angular module getter
    ngroute      // defines an Angular ngRoute 'when' definition
    ngrun        // defines a run phase function    
    ngstate      // creates an Angular UI Router state definition
    ```

**[Back to top](#table-of-contents)**

## Contributing

Open an issue first to discuss potential changes/additions. If you have questions, feel free to leave them as issues in the repository. If you find a typo, create a Pull Request (PR).

*By contributing to this repository you are agreeing to make your content available subject to the license of this repository.*

### Process
    1. Discuss the changes in a GitHub issue.
    2. Open a Pull Request (PR), reference the issue, and explain the change and why it adds value.
    3. The PR will be evaluated and either merged or declined.

**[Back to top](#table-of-contents)**

## License

Attributions are appreciated.

### Copyright

Copyright (c) 2015 Melissa Austin with code attribution to [https://github.com/johnpapa/angular-styleguide](https://github.com/johnpapa/angular-styleguide)

### (The MIT License)
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

**[Back to top](#table-of-contents)**
