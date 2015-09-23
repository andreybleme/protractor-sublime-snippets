# Protractor snippets
Protractor is an end-to-end test framework for AngularJS applications. Protractor runs tests against your application running
in a real browser, interacting with it as a user would.
This package is for Protractor **version 2.2.0**.

## Snippets

Below is a list of all snippets currently supported on this package and the
triggers of each one. The **⇥** means the `TAB` key.

### Locators
- `element by.id`: elbi⇥
- `element by.name`: elbn⇥
- `element by.css`: elbc⇥
- `element by.model`: elbm⇥
- `element by.binding`: elbb⇥
- `element.all by.id`: eabi⇥
- `element.all by.name`: eabn⇥
- `element.all by.css`: eabc⇥
- `element.all by.model`: eabm⇥
- `element.all by.binding`: eabb⇥
- `element.all by.repeater`: eabr⇥

### Element manipulation
- `element.clear`: elcl⇥
- `element.click`: elclk⇥
- `element.getAttribute`: elga⇥
- `element.getText`: elgt⇥
- `element.sendKeys`: elsk⇥

### Browser level 
- `browser.get`: brg⇥
- `browser.getLocationAbsUrl`: brgla⇥
- `browser.setLocation`: brsl⇥
- `browser.getCurrentUrl`: brgc⇥
- `browser.addMockModule`: bram⇥ 
- `browser.clearMockModules`: brcm⇥ 


## Install
To install **via git**, navigate to your Sublime Text Packages directory in your terminal:

OS X: `~/Library/Application\Support/Sublime\Text\2/Packages`

Windows: `%APPDATA%/SublimeText2/Packages/`

Linux: `~/.config/sublime-text-2/Packages/`

and paste the command:

`git clone git@github.com:andreybleme/protractor-sublime-snippets.git PSS`

To **install manually**, download this archive into a folder called *PSS* in your Sublime Text Packages directory (Preferences -> Browse Packages).

Make sure to restart Sublime Text when you're finished.

## Contributing

* Fork this repository
* Create a new branch for each kind of new snippet or improvement
* Ensure that your code is accompanied with tests
* Send a pull request from each feature branch


## License
The MIT License (MIT)

Copyright (c) 2015 [Lucas Andrey](http://andreybleme.com)

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
