# teamouy

A collection of configuration files containing prettier, eslint, stylelint, editor

# Use

in `.eslintrc.js`

```js
module.exports = {
  extends: [require.resolve('@asurraa/teamouy/dist/eslint')],

  // in antd-design-pro
  globals: {
    ANT_DESIGN_PRO_ONLY_DO_NOT_USE_IN_YOUR_PRODUCTION: true,
    page: true,
  },

  rules: {
    // your rules
  },
};
```

in `.stylelintrc.js`

```js
module.exports = {
  extends: [require.resolve('@asurraa/teamouy/dist/stylelint')],
  rules: {
    // your rules
  },
};
```

in `.prettierrc.js`

```js
const teamouy = require('@asurraa/teamouy');

module.exports = {
  ...teamouy.prettier,
};
```

### @AsurRaa 2021
