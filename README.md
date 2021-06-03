## 响应式编程

- 启动项目
- 开始第一个用户，浏览器打开url :http://localhost/user1.html
- 开始第二个用户，浏览器打开url :http://localhost/user2.html
- 模拟第一个用户的数据，会执行事件触发，浏览器打开url：http://localhost/sse/push?id=user1&content=test
- 模拟第一个用户的数据，会执行事件触发，浏览器打开url :http://localhost/sse/push?id=user2&content=test
- 模拟所有用户数据，会触发所有订阅事件的用户，浏览器打开url :http://localhost/sse/push-all?content=都来了啊