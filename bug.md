### ios iframe 不滚动
####在iframe外面加一个div，设置样式:
```
-webkit-overflow-scrolling:touch;
```

### placeholder 不居中
```
::-webkit-input-placeholder {
    /* WebKit browsers */
    　　text-align: center;
}

::-moz-placeholder {
    /* Mozilla Firefox 4 to 18 */
    　　text-align: center;
}

::-moz-placeholder {
    /* Mozilla Firefox 19+ */
    　　text-align: center;
}

::-ms-input-placeholder {
    /* Internet Explorer 10+ */
    text-align: center;
}
```
