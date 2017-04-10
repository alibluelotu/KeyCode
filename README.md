# KeyCode


1：从一个数组从获取随机的一个值

# var random=Math.floor(Math.random()*data.length);  #


2：通过keycode的值，来判断按下的键盘按键值

   此处值为13，用的是Enter键。
   
   ## keycode的值要处理兼容性 ##
   
   var event=event || window.event;
   var key=event.KeyCode||event.which||event.charCode;
