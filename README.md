# icon

[![Build Status](https://travis-ci.org/michaelliao/openweixin.svg?branch=master)](https://travis-ci.org/michaelliao/openweixin)

> [Element](https://github.com/ElemeFE/element) Icon clone, and did just a little change. If you have a better idea of this component improvement, please share it and I will update it immediately.

## Install

```bash
npm install vue-element-multiple-icon -S
```

## Quick Start

```bash
import Vue from 'vue'
import VmIcon from 'vue-element-multiple-icon'
import 'vue-element-multiple-icon/lib/icon.css'

Vue.component(VmIcon.name, VmRate)
```

## Usage

```html
<vm-icon type="load-a"></vm-icon>
```

## API
| Property | Description | Type | Default |
| ----- | ----- | ----- | ----- |
| tag | Name of tag. | String | i |
| type | Name of icon. | String | - |
| size | Size of icon.(default is px) | Number/String | - |
| color | Color of icon. | String | - |

For more information, please refer to [Icon](https://vue-element-multiple.github.io/icon) in our documentation.

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run demo:dev

# build for demo with minification
npm run demo:build

# build for gh-pages with minification
npm run demo:prepublish

# build for production with minification
npm run build

# generate gh-pages
npm run deploy
```

## LICENSE

[MIT](http://opensource.org/licenses/MIT)