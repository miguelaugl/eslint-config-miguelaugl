# eslint-config-miguelaugl
This is my eslint configuration for React and Node

[![CircleCI](https://circleci.com/gh/wcandillon/eslint-config-react-native-wcandillon.svg?style=svg)](https://circleci.com/gh/wcandillon/eslint-config-react-native-wcandillon)
[![npm version](https://badge.fury.io/js/eslint-config-miguelaugl.svg)](https://badge.fury.io/js/eslint-config-miguelaugl)

## Usage

```sh
# you also need eslint if not installed already: yarn add eslint --dev
yarn add eslint-config-miguelaugl --dev

or

# you also need eslint if not installed already: npm install eslint --save-dev
npm install eslint-config-miguelaugl --save-dev
```

## React

In `.eslintrc`:

```json
{ 
  "extends": "eslint-config-miguelaugl/react", 
} 
```

## Node

In `.eslintrc`:

```json
{ 
  "extends": "eslint-config-miguelaugl/node", 
} 
```