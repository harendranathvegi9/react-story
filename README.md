# React Story
`react-story` is a component for quickly and easily showcasing React components


<a href="https://travis-ci.org/tannerlinsley/react-story" target="\_parent">
  <img alt="" src="https://travis-ci.org/tannerlinsley/react-story.svg?branch=master" />
</a>
<a href="https://npmjs.com/package/react-story" target="\_parent">
  <img alt="" src="https://img.shields.io/npm/dm/react-story.svg" />
</a>
<a href="https://react-chat-signup.herokuapp.com/" target="\_parent">
  <img alt="" src="https://img.shields.io/badge/slack-react--chat-blue.svg" />
</a>
<a href="https://github.com/tannerlinsley/react-story" target="\_parent">
  <img alt="" src="https://img.shields.io/github/stars/tannerlinsley/react-story.svg?style=social&label=Star" />
</a>
<a href="https://twitter.com/tannerlinsley" target="\_parent">
  <img alt="" src="https://img.shields.io/twitter/follow/tannerlinsley.svg?style=social&label=Follow" />
</a>
<a href="https://cash.me/$tannerlinsley" target="\_parent">
  <img alt="" src="https://img.shields.io/badge/%24-Donate-brightgreen.svg" />
</a>

## Features
- A single, simple component
- Built-in optional routing
- Hyper-responsive, perfect for embedding in an existing UI

<!-- ## Demos and examples -->
<!-- - <a href="http://codepen.io/tannerlinsley/pen/QpeZBa?editors=0010" target="\_blank">Codepen</a>
- <a href="http://react-story.js.org/?selectedKind=2.%20Demos&selectedStory=Client-side%20Data&full=0&down=0&left=1&panelRight=0&downPanel=kadirahq%2Fstorybook-addon-actions%2Factions-panel" target="\_parent">Storybook</a> -->

## Table of Contents
- [Installation](#installation)
- [Example](#example)
- [Contributing](#contributing)

## Installation
1. Install React Story as a dependency
```bash
$ yarn add react-story
```
2. Import the `react-story` module
```javascript
// ES6
import ReactStory from 'react-story'
// ES5
var ReactStory = require('react-story').default
```
##### CDN
```html
  <!-- JS -->
  <script src="https://unpkg.com/react-story@latest/react-story.js"></script>

  <script>
    var ReactStory = window.ReactStory.default
  </script>
```


## Example
```javascript
import ReactStory from 'react-story'

render () {
  return (
    <ReactStory
      stories={[{
        name: 'Story 1',
        component: () => (
          <span>
            This is a React Story!
          </span>
        )
      }, {
        name: 'Story 2',
        component: () => (
          <span>
            Hey look! Another story.
          </span>
        )
      }, {
        name: 'Story 3',
        component: () => (
          <span>
            You get the idea :)
          </span>
        )
      }]}
    />
  )
}
```


## Contributing
To suggest a feature, create an issue if it does not already exist.
If you would like to help develop a suggested feature follow these steps:

- Fork this repo
- Install dependencies with `$ yarn`
- Auto-build files as you edit with `$ yarn run watch`
- Implement your changes to files in the `src/` directory
- Run the <a href="https://github.com/tannerlinsley/react-story">React Story</a> locally with `$ yarn run docs`
- View changes as you edit `docs/src`,
- Submit PR for review

#### Scripts

- `$ yarn run watch` Watches files and builds via babel
- `$ yarn run docs` Runs the storybook server
- `$ yarn run test` Runs the test suite

## Used By

<a href='https://nozzle.io' target="\_parent">
  <img src='https://nozzle.io/img/logo-blue.png' alt='Nozzle Logo' style='width:300px;'/>
</a>
