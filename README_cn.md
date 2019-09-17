[English](https://github.com/wangjiangs/CocosPay-Firefox-add-on/blob/master/README.md)
## CocosPay:

CocosPay 是一款Firefox附加组件， 该项目是基于Cocos-BCX公链的生态钱包.

## 准备工作:

安装8.9.3 或 以上版本的Node.js .



## 生成插件程序包:(代码中已经存在编译好的build文件，可直接安装使用，安装方式参照下面《安装插件》的提示步骤)

###### 按顺序执行下面命令

```
npm install
```

```
npm run build
```

运行结束项目中会生成一个 build 目录;


## 安装插件:
1. 打开FireFox浏览器 
2. 地址栏输入：`about:debugging#/runtime/this-firefox` 
3. 临时载入附加组件 
4. 选择build文件夹中的`manifest.json`文件 


## 配合Dapp使用插件

Here is a dapp sample. [cocos-dice](https://github.com/CocosBCX/cocos-dice)

