
fork来学习的java spring boot项目
感谢原作者  
原项目  
- [My-Blog](https://github.com/ZHENFENG13/My-Blog)


根据喜好修改了些排版,增加点功能，修改内容以后整合下

##----
---
关于mysql，5.5.3以下的版本不支持emoji表情（四个字节），5.5.3以上的也需要修改一下字符编码

上传文件的默认路径修改在Constants.java里


##----
---


更改了博客封面、头像、网站图标一些资源，排版作了小改动  
（如果页面过宽，会导致封面上下显示不全，不太懂html和css，但在封面上插入的文本可以强行让封面显示全:)

增加了日历功能，其中公历转农历用的是 [jjonline/calendar.js](https://github.com/jjonline/calendar.js)

去掉了按标签请求博客列表时对标签字符串的正则验证
