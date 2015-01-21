# jquery-event-key
返回 键盘事件触发时对应的按键值

###使用方法
```js
$("#test").onkeydown(function(event){
    var realKey = $.realKey(event);
    console.log(realKey);
});
```

