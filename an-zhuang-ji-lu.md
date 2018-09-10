## vue安装过程
```
- vue create
- babel/router/vuex/css pre-processors/linter/formatter
- stylus
- eslint + prettier
- lint on save
```


## vscode插件

- [x] ESLint
- [x] Prettier
- [x] Vetur
- [x] language-stylus
- [x] Stylus Supremacy


> 使用Iview时候 报：https://google.com/#q=vue%2Fno-parsing-error Parsing error: x-invalid-end-tag 解决办法:

```
// 添加rules配置
"vue/no-parsing-error": [2, { "x-invalid-end-tag": false }]
```

> stylus 编辑器配置

```
{

// 以下为stylus配置
"stylusSupremacy.insertColons": false, // 是否插入冒号
"stylusSupremacy.insertSemicolons": false, // 是否插入分好
"stylusSupremacy.insertBraces": false, // 是否插入大括号
"stylusSupremacy.insertNewLineAroundImports": false, // import之后是否换行
"stylusSupremacy.insertNewLineAroundBlocks": false // 两个选择器中是否换行
}
```

如需要在开发环境中MOCK数据，可使用[axios-mock-adpter](https://github.com/ctimmerm/axios-mock-adapter)插件


### 参考：

https://cn.vuejs.org/v2/style-guide/

https://github.com/pablohpsilva/vuejs-component-style-guide/blob/master/README-CN.md

https://github.com/ouvens/es6-code-style-guide

http://www.css88.com/archives/8345#functions

https://github.com/airbnb/javascript

https://github.com/lin-123/javascript

https://github.com/prettier/eslint-config-prettier

https://juejin.im/post/5b911f306fb9a05cdb1013b9?utm_source=gold_browser_extension