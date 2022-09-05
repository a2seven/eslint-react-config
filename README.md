## Description

ESLint config based in recommended best practices with custom rules

## Note

To install the package, add the **.nmprc** file to the root of your application with the following content:

```
@a2seven:registry=https://gitlab.com/api/v4/projects/<project_id>/packages/npm/

//gitlab.com/api/v4/projects/<project_id>/packages/npm/:_authToken=<your_token>
```

## Installation

```bash
$ npm install @a2seven/eslint-react-config
```

## How to usage

1. Add @a2seven/eslint-react-config package to your .eslintrc.js file:

```javascript
module.exports = {
    extends: [
        '@a2seven/eslint-react-config',
    ],
};
```
