# gatsby-remark-sub-sup

[![Build Status](https://travis-ci.org/winkey728/gatsby-remark-sub-sup.svg?branch=master)](https://travis-ci.org/winkey728/gatsby-remark-sub-sup)
[![codecov](https://codecov.io/gh/winkey728/gatsby-remark-sub-sup/branch/master/graph/badge.svg)](https://codecov.io/gh/winkey728/gatsby-remark-sub-sup)

Custom syntax to parse subscript and superscript. Rehype compatible (using `<sub>` and `<sup>`). Using [remark-sub-super](https://github.com/zestedesavoir/zmarkdown/tree/master/packages/remark-sub-super)

## Install

```bash
npm install --save gatsby-remark-sub-sup
```

## How to use

In your `gatsby-config.js`

```javascript
plugins: [
  {
    resolve: `gatsby-transformer-remark`,
    options: {
      plugins: [
        "gatsby-remark-sub-sup"
      ],
    },
  },
];
```

# License

[MIT](https://github.com/winkey728/gatsby-remark-sub-sup/blob/master/LICENSE)
