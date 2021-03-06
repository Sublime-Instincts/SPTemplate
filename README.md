# SPTemplate

![LICENSE](https://img.shields.io/badge/LICENSE-MIT-green?style=for-the-badge)

An opinionated template for Sublime Text Package development.

## Directory structure

```bash
│   .gitattributes
│   .gitignore
│   CHANGELOG.md
│   dependencies.json
│   LICENSE.md
│   messages.json
│   README.md
│   sp_template.py
│
├───.github
│       CONTRIBUTING.md
│       ISSUE_TEMPLATE.md
│       PULL_REQUEST_TEMPLATE.md
│
├───lib
│       __init__.py
│
├───messages
│       install.txt
│
├───resources
│   ├───commands
│   │       SPTemplate.sublime-commands
│   │
│   ├───keymaps
│   │       Default (Linux).sublime-keymap
│   │       Default (OSX).sublime-keymap
│   │       Default (Windows).sublime-keymap
│   │
│   ├───menus
│   ├───settings
│   │       SPTemplate.sublime-settings
│   │
│   └───syntax
│       └───tests
├───src
│       __init__.py
│
└───tests
        __init__.py

```

## Usage

Clone the repository into the ```Packages``` folder of Sublime Text 3 by going to ```Preferences -> Browse Packages ...```. Give a suitable name to the project, the root ```sp_template.py``` file as well as the resource files.

## License

Copyright 2019 © Ashwin Shenoy

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE. 