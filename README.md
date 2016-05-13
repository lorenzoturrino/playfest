Frontend Branch for Playfest (to refactor)


To set up:
1. fork the repo
2. npm install && bower install
3. ionic state restore

To run tests:
1. karma start test/karma.conf.js
protractor:
1. webdriver-manager update
2. webdriver-manager start
3. have backend running
4.  protractor test/protractor.conf.js

Deploy to mobile:
(in /app)
$ ionic platform add android
$ ionic build android
$ ionic run android
