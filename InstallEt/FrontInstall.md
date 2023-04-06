# VUE安装

## nvm

> Node.js：基于Chrome V8引擎的JS运行环境（javascript代码运行环境）
>
> npm： 第三方js插件包管理工具，会随着node一起安装（Node package Manager）
>
> npx：npm5.2之后新增的npx命令
> 		优点： 
> 		1、直接到当前项目node_moudle/.bin/路径和$PATH下，寻找命令
> 		2、避免全局安装，比如脚手架类型的库，通常只会在初始化时用一次，
> 		   此时就可以通过npmx create-react-app这种方式调用，执行这个命令时，
> 		    npx会将create-react-app下载到一个临时目录，使用完后再删除。

1. 简介：
   - node的版本管理器，可以方便地安装&切换不同版本的node
   - 