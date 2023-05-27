
## 简介

通过本项目，你可以使用 Markdown 书写简历，并通过 VuePress 部署为可预览的页面。
> 环境 node v16 ，不支持 node v18
如果环境使用 node v18
需要设置如下操作：
```
  "scripts": {
    "dev": "SET NODE_OPTIONS=--openssl-legacy-provider && vuepress dev resume",
    "build": "SET NODE_OPTIONS=--openssl-legacy-provider && vuepress build resume"
  },
```
> 参考：[node.js升级 digital envelope routines unsupported](https://www.bilibili.com/read/cv20854279)

[点击此处预览项目](https://siricee.github.io/Resume-vuepress)
[Resume-vuepress](https://github.com/Siricee/Resume-vuepress)

> 来源于这个项目 [wannaxiao/vuepress-theme-resume](https://github.com/wannaxiao/vuepress-theme-resume)<br>
> 原项目依赖`VuePress v0.10.0`，本人在VuePress更新至正式版`v1.0.2`时将其重写。


## 使用

```bash
git clone https://github.com/Siricee/Resume-vuepress.git
cd Resume-vuepress
npm install
```
在`resume`文件夹内，根据`scaffold.md`修改`README.md`并保存，后执行以下命令
```bash
npm run dev 	# 预览
npm run build	# 生成静态页面
```


**打印简历**：

Chrome 页面中右键 -> 打印 -> 另存为 pdf。

*注意：打印-更多设置-取消勾选页眉和页脚。否则会有标题和日期。*

## 部署

Github-Pages部署说明：

本项目的部署条件

