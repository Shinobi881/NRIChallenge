# NRIChallenge
Coding challenge for No Red Ink

*Your task is to create a test runner that runs automated tests in the browser and reports on their results as soon as each test completes.*

###User Story
- All 6 tests should be run simultaneously

- The user interface should communicate the following, using whatever design you like:
  - The current status of each test (Not Started Yet, Running, Passed, or Failed)
  - How many total tests have passed so far
  - How many total tests have failed so far
  - How many total tests are still running
  - An indication (e.g. "FINISHED!") when all tests have completed running
  - Initially each test is in the Not Started Yet state, the user must press a button to start them running. 
  Once they are running, the interface should update in realtime without further user interaction.

#Installation
*Instructions for building with webpack*

1. `$ npm install -g webpack` 
2. `$ npm install -dwebpack-dev-server`                
4. `$ webpack-dev-server`
5. Open a browser window and navigate to `localhost:8080/app`

#Contributing
*Please adhere to the style and contribution guides when making pull request and be courteous and appropriate when adding/commenting on issues*

1. [Contribution Guide](CONTRIBUTING.md)
2. [Style guide](STYLE-GUIDE.md)
3. [Closing issues via coomits](https://help.github.com/articles/closing-issues-via-commit-messages/)