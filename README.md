# React + TypeScript + Vite Boilerplate

npm create vite@latest

## Install airbnb config
https://www.npmjs.com/package/eslint-config-airbnb

npx install-peerdeps --dev eslint-config-airbnb

Update eslint extends rule within configuration

"airbnb", "airbnb/hooks"

## airbnb support for typescript

https://www.npmjs.com/package/eslint-config-airbnb-typescript

npm i -D eslint-config-airbnb-typescript

Update eslint extends rule within configuration

'airbnb-typescript'

Add Parser Options

parserOptions: {
    project: './tsconfig.json'
}

Run ESLint

npx eslint . --ext .js,.jsx,.ts,.tsx

## prettier support

npm i -D prettier eslint-plugin-prettier eslint-config-prettier

[eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier)
eslint-plugin-prettier
Runs Prettier as an ESLint rule and reports differences as individual ESLint issues.

- create prettier cjs file and add desired settings

eslint-config-prettier
Turns off all rules that are unnecessary or might conflict with Prettier.
