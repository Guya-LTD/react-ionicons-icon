<!-- Alignment options!!!!! -->
<img align="center"  src="ionicons-og-image.png">

# React ionicons icon

> Made with create-react-library

[![NPM](https://img.shields.io/npm/v/react-ionicons-icon.svg)](https://www.npmjs.com/package/react-ionicons-icon) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

react-ionicons-icon is a collection of [Ionicons](ioniconlink) icons in react component.

Generating react component from ionicons svg files, this project is based on the blog post https://emasuriano.com/blog/building-a-maintainable-icon-system-for-react-and-react-native source code of the blog can be found on https://github.com/EmaSuriano/maintainable-icon-system-react

Ioniocns description:- 

|Icon Library|License|Version|
|---|---|---|
|[Ionicons](https://ionicons.com/)|[MIT](https://github.com/ionic-team/ionicons/blob/master/LICENSE)|5.2.3|

## Install

```bash
npm install --save react-ionicons-icon
```

## Usage

```jsx
import React, { Component } from 'react'

import { 
  Accessibility, // Filled Icon
  AccessibilityOutline, // Outlined Icon
  AccessibilitySharp, // Sharp Icon
  } from 'react-ionicons-icon';

import 'react-ionicons-icon/dist/index.css' // Optional, changes all outlined svg strock color

class Example extends Component {
  render() {
    return <Accessibility />
  }
}
```

For using other icons refer to [Ionicons](https://ionicons.com/).
Example:-

```jsx
<ion-icon name="battery-full"></ion-icon> // Becomes <BatteryFull />
<ion-icon name="battery-full-outline"></ion-icon> // Becomes <BatteryFullOutline>
<ion-icon name="battery-full-sharp"></ion-icon> // Becomes <BatteryFullSharp />
```

### Size

To change size of the svg icon use `size` props:

```jsx
<Accessibility size="32px">
```

## API

|Key|Default|Descripton|
|---|---|---|
|`size`|`32px`|Icon size|
|`fill`|`#373737`|Icon filling color|

## License

MIT © [Simonbelete](https://github.com/Simonbelete)


[ioniconlink]: https://ionicons.com/
[ioniconlicenselink]: https://github.com/ionic-team/ionicons/blob/master/LICENSE