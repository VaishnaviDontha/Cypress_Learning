![Cypress Logo](https://www.cypress.io/static/cypress-io-logo-social-share-8fb8a1db3cdc0b289fad927694ecb415.png)

![npm](https://img.shields.io/npm/v/npm) ![Cypress](https://img.shields.io/badge/Cypress.io-v8.3.1-blue)
![madeby](https://img.shields.io/badge/Documented%20By-Vaishnavi%20Dontha-blue)

# Cypress_Learning
*This Repo includes all about Cypress.io for QA*

#### Required Tech-Stack
* Cypress
* VSCode or any IDE
* JavaScript
* Mocha

### Why Cypress?
It’s a test automation tool, similar to Selenium WebDriver, WebDriverIO, TestCafe, and others.
Also referred as a next generation front end testing tool built for the modern web.

It is comparatively different because, it was built **_by_** frontend developers, and **_for_** frontend developers. And this can be seen by some design decisions that were taken when building this tool.

**Secondly, it is a JavaScript-only tool. And, it is not only a automation tool -- It's a Testing Tool!**

### What's different about Cypress
* Does **NOT** use Selenium.
* Javascript only!
* Dev & QA Friendly
* All-in-one End-to-End Testing Framework

### Who can use Cypress
QA engineers building or testing web applications using modern JavaScript frameworks.

### Features
Here is a list of things it can do that no other testing framework can:

1. _**Time Travel:** Takes snapshots as your tests run. Hover over commands in the Command Log to see exactly what happened at each step of the test._
2. _**Debuggability:** Stop guessing why your tests are failing. Debug directly from familiar tools like Developer Tools. Our readable errors and stack traces make debugging lightning fast._
3. _**Automatic Waiting:** Never add waits or sleeps to your tests. Cypress automatically waits for commands and assertions before moving on. No more async hell._
4. _**Spies, Stubs, and Clocks:** Verify and control the behavior of functions, server responses, or timers. The same functionality you love from unit testing is right at your fingertips._
5. _**Network Traffic Control:** Easily control, stub, and test edge cases without involving your server. You can stub network traffic however you like._
6. _**Consistent Results:** Cypress doesn’t use Selenium or WebDriver. Say hello to fast, consistent and reliable tests that are flake-free._
7. _**Screenshots and Videos:** View screenshots taken automatically on failure, or videos of your entire test suite when run from the CLI._
8. _**Cross browser Testing:** Run tests within Firefox and Chrome-family browsers (including Edge and Electron) locally and optimally in a Continuous Integration pipeline._

### Lets get started with the Tests like - Setting it up, Writing, Running, Debugging and its Types
* Setting up Tests - Cypress doesn't need any drivers, or dependencies to install or configure.
* Writing Tests - It is very easy to understand and read the code written.
* Running Tests - It runs as fast as a browser with all the log details in it.
* Debugging - Cypress has readable error messages, to help us to debug quickly. We can also verify the same in the console tab of the developer tools.
* Test Types - It holds End-to-End, Component, API Tests, etc.

### Trade-Offs
* Browser Support
* Native Mobile app Supoort
* Multiple browser\tabs
* Same Origin

### Basic Architecture

Below, is a pictorial representation of testing frameworks before and with Cypress -
![Cypress](https://www.toolsqa.com/gallery/Cypress/1.Difference%20between%20cypress%20and%20Non%20Cypress%20based%20test%20frameworks.png)

Most of the testing tools execute their tests by running outside of the browser and executing remote commands across the network. But, Cypress executes directly inside the browser. In other words, it is the browser that is executing your test code.
It enables Cypress to listen and modify the browser behavior at run time by manipulating DOM and altering Network requests and responses on the fly.
It open doors to new kind of testing along with ultimate control over your application (front and back).

![Architecture](https://user-images.githubusercontent.com/17179877/74605728-8e547a80-50c2-11ea-8549-b804ef9b4996.png)

# Getting Started
### Installation and Prerequisites
1. Ensure we've latest **node.js, npm** installed in the system.
  > Can be verified the version via
    >     **_node -v_** and
    >     **_npm -v_**
  * Also be installed here ![node.js](https://nodejs.org/en/download/) ![NPM](https://docs.npmjs.com/cli/v7/commands/npm-install)
   > On completion,  initialise NPM via
   > _**npm init**_
   > This creates _package.json_ which is the heart of the project. It holds all the dependencies. _(Similar to a POM.xml)_ and can also be viewed via **_npm init -y_** in the terminal.
2. Cypress Installation: Navigate to the project path and execute
  > _**npm install cypress --save-dev**_
  * OR via Yarn ![downloadable here](https://yarnpkg.com/)
  > _**yarn add cypress --dev**_
  * OR via Direct Download ![here](https://download.cypress.io/desktop) - Can be used when not using Node or npm in your project or you want to try Cypress out quickly.

** If in case your IDE throws any Error as Unrestricted try executing -
> **Set-ExecutionPolicy -Scope CurrentUser Unrestricted**


Official documentation - ![here](https://docs.cypress.io/)
