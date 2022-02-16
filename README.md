# postcss-tailwind-mp
[PostCSS] 用于兼容tailwind和小程序的css插件

---
[postcss]: https://github.com/postcss/postcss

## Installation
```
npm install postcss-tailwind-mp --save-dev
```

## Usage
### rollup
```
postcss({
    plugins: [
      require('autoprefixer'),
      require('postcss-tailwind-mp')
    ]
  }),

```

### postcss.config.js
```
module.exports = ({ env }) => {
  plugins: [
    require('postcss-tailwind-mp')
  ]
}
```
