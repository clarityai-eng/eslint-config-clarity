Clarity eslint shareable config

## Usage

Install module and its dependencies.

    npm i babel-eslint eslint eslint-config-clarity eslint-config-standard eslint-plugin-import eslint-plugin-node eslint-plugin-promise eslint-plugin-standard eslint-plugin-vue --save-dev
    npm i "github:clarityai-eng/eslint-config-clarity#1.0.0" --save-dev
    
Create a .eslintrc.js in the root of your project with the following content

```js
module.exports = {
  extends: ['eslint-config-clarity'],
};
```

Now you can run eslint with something like: `eslint src`
