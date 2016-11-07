Django常见问题与解答
## 本FAQ为群Django中国 122241953 资料收集使用
## 如果本FAQ确实对你的工作和生活有帮助，请在群里积极发红包致谢，谁的时间也不是免费的。



### 1. 我有****问题，该怎么做？
### 很多问题的解答都在官方文档，地址：https://docs.djangoproject.com
使用方法：
- 打开链接：
- 在浏览器用快捷键，如Ctrl+F，搜索关键词，如url/session/password
- 通读一遍，搜索关键词定位解决方案。如果还有问题，提问模式如下：我有某某问题，看了某某文档，地址为https://******* ，它提到A解决方案，但是不能解决我的问题B，请问该怎么办
- 如，我有问题“django怎么保持用户登录状态呢？我用session，结果关了浏览器还是已经登陆”
- 打开上述链接https://docs.djangoproject.com
- 在浏览器用快捷键，如Ctrl+F，搜索关键词，session
- 通读一遍，搜索关键词expire，最后发现一段话，意思是：You can control whether the session framework uses browser-length sessions vs. persistent sessions with the SESSION_EXPIRE_AT_BROWSER_CLOSE setting.就是说你可以在settings.py里，控制SESSION_EXPIRE_AT_BROWSER_CLOSE参数，确定用户的session在关闭浏览器后的行为。

