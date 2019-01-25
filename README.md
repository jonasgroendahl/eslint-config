Prettier + ESLint:

1. https://blog.echobind.com/integrating-prettier-eslint-airbnb-style-guide-in-vscode-47f07b5d7d6a
2. `npm i -D babel-eslint`
3. add property to eslint.config: `parser: "babel-eslint"`
4. add new rule to rules in eslint.config: "react/jsx-filename-extension": [1, { "extensions": [".js", ".jsx"] }]
