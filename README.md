# WebStorm Live Templates

A collection of live templates for JetBrains WebStorm => 10

## Table of Contents

  1. [Motivation](#motivation)
  1. [Installation](#installation)   
  1. [Abbreviations](#abbreviations)
  1. [Contributing](#contributing)
  1. [License](#license)

## Motivation

These live templates were adapted for the [johnpapa/angular-style repo] (https://github.com/johnpapa/angular-styleguide) in response to [issue #529] (https://github.com/johnpapa/angular-styleguide/issues/529). 

## Installation

In the near future you can download an archive file via the [johnpapa/angular-style repo] (https://github.com/johnpapa/angular-styleguide) but for now you can clone this repo and follow these steps:

    - Open the project in WebStorm
    - Expand the angular folder and open the first file, angular.controller.js
    - Ctrl+A to highlight the file contents
    - Navigate to Tools > Save as Live Template...
    - Type the abbreviation, i.e., ngcontroller, into the `Abbreviation` field and enter a description, i.e., Creates an Angular controller
    - Select `Edit variables` and enter a value into the `Default values` field for each variable, i.e., "moduleName", "ControllerName", "dependency"
    - Click `OK` to save the default values
    - Click `OK` to save the live template
    
*Repeat these steps for each JavaScript file in the angular folder using the corresponding [abbreviation] (#abbreviations)*
    
## Abbreviations

To use the new live templates simple open a new JavaScript file and type the following abbreviations followed by a `TAB`:

    ```javascript
    ngcontroller // Creates an Angular controller
    ngdirective  // Creates an Angular directive
    ngfactory    // Creates an Angular factory
    ngmodule     // Creates an Angular module
    ngservice    // Creates an Angular service
    ngfilter     // Creates an Angular filter
    ```

**[Back to top](#table-of-contents)**

## Contributing

Open an issue first to discuss potential changes/additions. If you have questions, feel free to leave them as issues in the repository. If you find a typo, create a Pull Request (PR). The idea is to keep the content up to date and use github’s native feature to help tell the story with issues and PR’s, which are all searchable via google.

*By contributing to this repository you are agreeing to make your content available subject to the license of this repository.*

### Process
    1. Discuss the changes in a GitHub issue.
    2. Open a Pull Request (PR), reference the issue, and explain the change and why it adds value.
    3. The PR will be evaluated and either merged or declined.

## License

Attributions are appreciated.

### Copyright

Copyright (c) 2015 Melissa Austin with code attribution to [https://github.com/johnpapa/angular-styleguide] (https://github.com/johnpapa/angular-styleguide)

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
