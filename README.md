# @rss/eslint-config

## What’s included?

- React: @rss/eslint-config-react
- Next.js: @rss/eslint-config-next
- Angular: @rss/eslint-config-angular
- Node.js: @rss/eslint-config-node

Each preset provides a curated set of ESLint rules, plugins, and parser settings tailored to that environment.

## Setup

### React with Next.js

``` 
npm install --save-dev eslint @rss/eslint-config-next
```

create `.eslintrc.json`
```
{
  "extends": [
    "@rss/eslint-config-next",
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)
```
npm install --save-dev eslint @rss/eslint-config-react
```
create `.eslintrc.json`
```
{
  "extends": [
    "@rss/eslint-config-react"
  ]
}
```

### Angular
```
npm install --save-dev eslint @rss/eslint-config-angular
```

create `.eslintrc.json`
```
{
  "extends": [
    "@rss/eslint-config-angular"
  ]
}
```

### Node.js

```
npm install --save-dev eslint @rss/eslint-config-node
```
create `.eslintrc.json`
```
{
  "extends": [
    "@rss/eslint-config-node"
  ]
}
```
© 2025 Renan de Souza Silva