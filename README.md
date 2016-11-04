# meteor-css-issue

https://github.com/meteor/meteor/issues/8008

## Reproduction Steps

1. Run `meteor`
2. Add a new file `main.less` to the `imports` folder
3. Uncomment the `import` in `client/main.js`
4. Open the console on `http://localhost:3000`

The console shows `Uncaught Error: Cannot find module './main.less.css'`
