# vanilla-sharing

Small simple tool for sharing url, title, description and image to VK, Facebook, OK, G+, Twitter and Mail

[![Build Status](https://travis-ci.org/avdeev/vanilla-sharing.svg?branch=master)](https://travis-ci.org/avdeev/vanilla-sharing)

# Installation

```sh
npm install --save vanilla-sharing
```

or

```sh
yard add vanilla-sharing
```

# Usage

1. From build folder. Include file build/vanilla-sharing.js to your project

2. From ES6 modules.

```js
import { vk, ok, fb, gp, tw, mail } from 'vanilla-sharing';
```

# API

For install from build folder as global library

```js
VanillaSharing.vk({ url: 'https://google.com' });

VanillaSharing.fb({ fbAppId: '123', url: 'https://google.com' });

VanillaSharing.ok({ url: 'https://google.com' });

VanillaSharing.gp({ url: 'https://google.com' });

VanillaSharing.tw({ url: 'https://google.com' });

VanillaSharing.mail({ url: 'https://google.com' });
```
