## CN

将多个函数组合成一个函数。

每个函数使用下一个函数的返回值作为参数。

|参数名|类型|说明|
|-----|----|---|
|...fn|function|要组合的函数|
|返回值|function|目标函数|

```javascript
var welcome = compose(function (name) 
{
    return 'hi: ' + name;
}, function (name) 
{
    return name.toUpperCase() + '!';
});

welcome('licia'); // -> 'hi: LICIA!'
```