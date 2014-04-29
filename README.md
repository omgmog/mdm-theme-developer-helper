MDM Theme Developer Helper
==========================

Some functions that make it possible to develop MDM Webkit Greeter themes in the browser

I'm still working on this, but it's basically a recreation of the environment provided by https://github.com/linuxmint/mdm/blob/master/gui/mdmwebkit.c so that you can developer your MDM Webkit greeter themes in your browser.

### Features
- populates with some dummy content
- parses MDM theme variables (e.g. `$enter_your_username_label`)
- catches `alert()` calls in theme and handles them


### Usage
- Include `dummy.js` in your theme before your theme javascript
- Develop your theme in your browser, as you would any other website
