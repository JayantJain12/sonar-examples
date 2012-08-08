This example demonstrates how to analyse JavaScript project with Sonar Runner reusing reports generated by JsTestDriver.

Prerequisites
=============
* Sonar 2.11 or higher
* Sonar JavaScript Plugin 1.0 or higher
* Sonar Runner 1.3 or higher

Usage
=====
* In run-tests.bat, replace <path_to_browser> by the path to your browser executable. Examples with Chrome:
** Windows: C:\Users\myUser\AppData\Local\Google\Chrome\Application\chrome.exe
** Mac: /Applications/Google Chrome.app/Contents/MacOS/Google Chrome
* Run the tests by executing "run-tests.bat" to execute JsTestDriver unit tests and gather code coverage statistics
* Run the following command: "sonar-runner" to analyse JavaScript code with Sonar and import unit test results