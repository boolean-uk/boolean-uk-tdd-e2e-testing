# Test-Driven Development

## End to End testing

### Learning Objectives
- Setup and use an E2E test framework to help test-drive a frontend application
- Use the Red Green Refactor loop to develop a feature

### Quickstart
1. Fork this repository
2. Clone your fork to your local machine
3. Install project dependencies
```sh
$ npm ci # to install dependencies
```

### Run the app locally
```sh
$ npm start
# point your browser to localhost:5000
```

### Run cypress
```sh
# in another terminal shell
$ npx cypress open
```

### Instructions

Follow a test-driven development process. Start with creating a domain model, then write a test, and pass it by writing source code. Repeat until you've finished.

### Requirements

#### Part1
- Create a todo item that has text
- Show all todo items

#### Part 2
- Use data from GitHub's API and show a count of repositories for any GitHub username
- Intercept network requests using `cy#intercept()` and stub the response with a fixture

### Resources
- [Cypress intro](https://docs.cypress.io/guides/getting-started/writing-your-first-test#Add-a-test-file)
- [Cypress basics](https://docs.cypress.io/guides/getting-started/testing-your-app#Step-1-Start-your-server)
- [Cypress simple](https://docs.cypress.io/guides/core-concepts/introduction-to-cypress#Cypress-Can-Be-Simple-Sometimes)
- [Cypress interactions](https://docs.cypress.io/guides/core-concepts/interacting-with-elements#Actionability)


#### Further work

- Test-drive using a checkbox to toggle whether a todo item is complete or not.
- Use Jest & Testing Library to test-drive a component
- Extend your todo app. Use the requirements and your code from https://github.com/boolean-uk/boolean-uk-tdd-todo-app#requirements. How can you reuse your work in a frontend app?
