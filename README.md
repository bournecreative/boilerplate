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