# 通用短信/邮件验证码类库说明文档

1.0版本，目前支持的登录平台包括：

* Email
* 极光
* 阿里
* 腾讯

### 安装

```
composer require iredcap/valid-code
```

> 类库使用的命名空间为`\\iredcap\\Code`

### 目录结构

```
.
├── src                              代码源文件目录
│   ├── Contracts
│   │   ├── Gateway.php              必须继承的抽象类
│   │   └── GatewayInterface.php     必须实现的接口
│   ├── Gateways
│   │   ├── Jpush.php
│   │   ├── Qsms.php
│   │   ├── Email.php
│   ├── Support
│   │   └── Str.php                  字符串辅助类
│   └── Code.php                     抽象实例类
├── README.md                        说明文件
├── composer.json                    composer文件
```
### 其他
使用中如果有什么问题，请提交issue，我会及时查看
