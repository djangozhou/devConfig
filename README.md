[TOC]


### 简介
这是一份关于eslint规则的配置文件，主要来自[@PanjiaChen](https://github.com/PanJiaChen/vue-element-admin)的代码规范。

### 使用
- 依赖

    1. 下载npm包
        - eslint
        - eslint-friendly-formatter
        - eslint-loader
        - eslint-plugin-html

    2. 复制或者下载配置文件放置到项目根目录
- vscode

在首选项中->设置->增加如下代码用来校验规则：
```
"files.autoSave": "off",
"eslint.validate": [
    "javascript",
    "javascriptreact",
    "html",
    {
        "language": "vue",
        "autoFix": true
    }
],
"eslint.options": {
    "plugins": [
        "html"
    ]
},
```
同时增加以下代码用来保存时根据eslintrc配置来格式化代码
```
"eslint.autoFixOnSave": true
```

### TO DO
- [ ] 汉语注释所有的规则
- [x] 在实际工程中运用此规则
- [ ] 养成习惯
