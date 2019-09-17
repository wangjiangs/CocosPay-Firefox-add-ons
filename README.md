  [中文](https://github.com/wangjiangs/CocosPay-Firefox-add-ons/blob/master/README_cn.md)

## CocosPay:

CocosPay is an ecosystem wallet that based on Cocos-BCX public chain as a FireFox add-ons

## Preparation:
node.js 8.9.3+


## Build plugin package, run: 

```
npm install
```

```
npm run build
```

you'll find a folder named `build` after running above commands

## Install extensions:
1. Open the FireFox browser
2. Address bar input: about:debugging#/runtime/this-firefox
3. Temporarily load add-ons
4. Select the manifest.json file in the build folder that built before.


## Using Cocospay on DApp

Here is a dapp sample. [cocos-dice](https://github.com/CocosBCX/cocos-dice-sample) 

