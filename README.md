#ESLint + Prettier with VSCode

1. In VSCode: install 2 extensions extensions: ESLint & Prettier
2. VSCode preference setting:

- check `Prettier:Single Quote`
- check `Format On Save`

3. install npm packages:

   > npm i -D eslint prettier eslint-plugin-prettier eslint-config-prettier eslint-plugin-node eslint-config-node

4. go to https://www.npmjs.com/package/eslint-config-airbnb

   > npx install-peerdeps --dev eslint-config-airbnb

5. in the root, create `.prettierrc` JSON file and put rules

- for more rules, refer to https://prettier.io/docs/en/options.html

6. in the root, create `.eslintrc.json`

- for more rules, refer to https://eslint.org/docs/rules/
