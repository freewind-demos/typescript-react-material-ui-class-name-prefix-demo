TypeScript React "material-ui" Class Name Prefix Demo
===================================

在需要的情况下，可以使用`StylesProvider`让material-ui在生成每个class前都加一个特定的前缀，
这样生成的className就会像

```
.myPrefix-MuiAutocomplete-input
```

不过需要注意的是，如果想override，还需要自定义一个container class，才能正确覆盖。

参看hello.css中注释

```
npm install
npm run demo
```
