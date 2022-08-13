# icon-pack
# Ionicons React Component

This package contains a React Component, which implements the latest version of the official [icon-pack](https://github.com/hackxtar/icon-pack) into React or any other node laibrary.

## Installation 📦

To add the package to your existing node project just type in one of the following commands:

```
npm i icon-pack
```

or

```
yarn add icon-pack
```

## Usage

```js
import React from 'react';
import HomeIcon from 'icon-pack';

export const Component = () => (
  <>
    <HomeIcon />
  </>
);
```

### Custom Size

You can specify the icon size by using the optional `size` prop.

```js
<HomeIcon name="bag-outline" size="small" />
<HomeIcon name="bag-outline" size="large" />
```

## Supported Icons

This package supports all icon-pack of the matching version. To see a full list of them
