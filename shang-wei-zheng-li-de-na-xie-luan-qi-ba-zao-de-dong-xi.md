看英文文档时的混淆的地方

argument

argument对应的是value。argument就是自变量，value就是因变量

statement vs expression

statement：something that you say or write in a formal or official way。声明（暂时翻译）

expression：the act of making your thoughts, feelings。表达

向组件传入点击事件的两种方式，不太能理解

```js
<Footer
    visibilityFilter={visibilityFilter}
    onFilterClick={filter=>store.dispatch({
            type:"SET_VISIBILITY_FILTER",
            filter
        })
    }
/>
```



