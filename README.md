
The most simple form of web component only supported by chrome as we do not include any polyfill. 

##Description

The idea was to test the very basic ways to interact with a web component

- Create 2 instances of same web component
- Pass "option" object to each instance containing
	- static information to pass to render
	- callback functions to be called on button click

##Run the example

Simply open the `index.html` page in Chrome. To do so, you will need to run chrome with the following options (on windows)

`chrome.exe --disable-web-security --user-data-dir=C:\WHATEVER_YOU_WANT`
