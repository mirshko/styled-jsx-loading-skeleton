# styled-jsx-loading-skeleton

> Super light-weight loading skeleton for apps already using styled-jsx

[![NPM](https://img.shields.io/npm/v/styled-jsx-loading-skeleton.svg)](https://www.npmjs.com/package/styled-jsx-loading-skeleton)

Heavily based upon [@dvtng](https://github.com/dvtng)'s [react-loading-skeleton](https://github.com/dvtng/react-loading-skeleton).

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
import React from "react";

import Skeleton from "styled-jsx-loading-skeleton";

const LoadingScreen = () => {
  return (
    <Fragment>
      <Skeleton height={32} widht={32} circle />
      <Skeleton width={300} height={24} />
      <Skeleton width={100} height={24} />
      <Skeleton width={30} height={24} />
    </Fragment>
  );
};
```

Add the below css to your app's main css file.

```css
:root {
  --skeleton-base-color: hsl(210deg 9% 96%);
  --skeleton-highlight-color: hsl(210deg 9% 98%);
}
```

### Themeing

To change the base and highlight color of the component, add this to your root or to any wrapping component to directly change the color of the components.

```css
:root {
  --skeleton-base-color: grey;
  --skeleton-highlight-color: lightgrey;
}
```

To adjust the duration of the animation, the `Skeleton` component accepts a property named `duration` acceping a number in seconds of how long to animate the highlight across the width of the element for.

## Previous Art

- [react-loading-skeleton](https://github.com/dvtng/react-loading-skeleton);

## License

MIT © [mirshko](https://github.com/mirshko)
