# Eslint Config

This module helps you to write beautiful code in javascript with proper js conventions.
You can copy, edit or change the config as per your requirement

## How To Use

Make a file named `.eslintrc` with following contents:

```json
{
  "extends": "paradox",
  "rules": {
  }
}
```

Now run:

```bash
npm install --save-dev eslint babel-eslint eslint-plugin-babel eslint-plugin-import eslint-config-paradox
# Now you can run eslint on src folder using
eslint src
```