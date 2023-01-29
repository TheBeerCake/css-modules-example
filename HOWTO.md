**How to use css modules with CRA**

1. Add package `yarn add -D typescript-plugin-css-modules` or `npm install -D typescript-plugin-css-modules` alternativeley.
2. Once installed, add this plugin to your `tsconfig.json`:

```javascript
{
  "compilerOptions": {
    "plugins": [{ "name": "typescript-plugin-css-modules" }]
  }
}
```

3. Rename your `*.css` files to `*.module.scss`.
4. Update imports in your `*.tsx` files.
5. If you are using VS Code: Open a tsx file and click the `{}` icon on the bottom right of the editor UI and click "select version" and then chose workspace version. This will create a `.vscode` folder with configuration.

For cases when intellisense still does not work try to restart VS Code window or you can add CSS Modules VS Code plugin by clinyong
