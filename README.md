# styled-jsx-loading-skeleton

> Super light-weight loading skeleton for apps already using styled-jsx

[![NPM](https://img.shields.io/npm/v/styled-jsx-loading-skeleton.svg)](https://www.npmjs.com/package/styled-jsx-loading-skeleton)

## Install

```bash
npm install --save styled-jsx-loading-skeleton
```

### Yarn

```bash
yarn add styled-jsx-loading-skeleton
```

## Usage

```jsx
import React from 'react'

import Skeleton from 'styled-jsx-loading-skeleton'

const LoadingScreen = () => {
  return (
    <Fragment>
      <Skeleton width={300} height={24} />
      <Skeleton width={100} height={24} />
      <Skeleton width={30} height={24} />
    </Fragment>
  )
}
```

## License

MIT © [mirshko](https://github.com/mirshko)
