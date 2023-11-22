## 外卖点餐系统

该项目基于**SpringBoot + MyBatis**实现，并使用了 Vue.js 与 ElementUI 作为前端框架。包括客户端与服务端两个模块，其中用户可以用过客户端浏览外卖内容并进行下单，商家可以通过服务端进行订单的管理工作。

- 负责完成了后端的开发工作

---

### 服务端功能

```
http://localhost:8088/backend/index.html
```

- 商家注册与登录
- 查看菜品内容并进行管理
- 查看订单并进行管理

### 客户端功能

```
http://localhost:8088/front/index.html
```

- 客户注册与登录
- 使用手机收取验证码并进行登录
- 查看菜品内容
- 添加菜品至购物车
- 查看购物车功能并进行修改
- 编辑用户收取地址
- 进行下单

---

### 技术栈

- SpringBoot: 用于构造后端框架
- MyBatis-Plus: 用于实现数据库的处理
- MySQL: 数据库
- Maven: 用于构建项目并进行项目的依赖管理
- Postman: 用于做接口请求测试

---

- 该项目源自[《瑞吉外卖》](https://www.bilibili.com/video/BV13a411q753/)
- 该项目仍有许多改进之处，仅供学习参考。