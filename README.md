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
- `browser.pause`: brp⇥ 
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

To **install manually**, [download the most recent release](https://github.com/andreybleme/protractor-sublime-snippets/releases)  into a folder called *PSS* in your Sublime Text Packages directory (Preferences -> Browse Packages).

Make sure to restart Sublime Text when you're finished.

## Contributing

* Fork this repository
* Remember testing the submitted snippet
* Send a pull request with your new feature
