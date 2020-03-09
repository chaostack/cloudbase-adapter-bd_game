## cloudbase-adapter-bd_game

[![NPM Version](https://img.shields.io/npm/v/cloudbase-adapter-bd_game.svg?style=flat)](https://www.npmjs.com/package/cloudbase-adapter-bd_game)
[![](https://img.shields.io/npm/dt/cloudbase-adapter-bd_game.svg)](https://www.npmjs.com/package/cloudbase-adapter-bd_game)

tcb-js-sdk百度小游戏适配器

## 安装
### npm
```bash
npm i cloudbase-adapter-bd_game -S
```

### Unpkg
可以使用unpkg托管的js文件，地址如下：
https://unpkg.com/cloudbase-adapter-bd_game/dist/index.js

## 使用
### ES Module
```javascript
import tcb from 'tsb-js-sdk';
import adapterForWxMp from 'cloudbase-adapter-bd_game';

// 以下两种方式二选一
// 1.单参数传入
tcb.useAdapters(adapterForWxMp);
// 2.数组形式传参
tcb.useAdapters([adapterForWxMp]);
// adapter必须在init之前传入
tcb.init();
```

### CommonJS
```javascript
const tcb = require('tsb-js-sdk');
const adapterForWxMp = require('cloudbase-adapter-bd_game');

// 以下两种方式二选一
// 1.单参数传入
tcb.useAdapters(adapterForWxMp.adapter);
// 2.数组形式传参
tcb.useAdapters([adapterForWxMp.adapter]);
// adapter必须在init之前传入
tcb.init();
```