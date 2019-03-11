# UITestsBelong

Notes:
chromedriver and geckodriver present in this repo macOS compatible.
please replace respective drivers with Platform you are going to run from below url

ChromeDiver
https://chromedriver.storage.googleapis.com/index.html?path=72.0.3626.69/

FirefoxDriver
https://github.com/mozilla/geckodriver/releases/tag/v0.21.0

Command to runtest

mvn clean test -Dbrowser=chrome

OR

mvn clean test -Dbrowser=firefox

Note: This test can be run uninterrupted(No datasetup required) because emailId will be generated with Random number example: test3456@testauto.com
