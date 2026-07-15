# WeChat Mini Program Jump Demo

一个用于演示“网页跳转微信小程序”的静态页面示例。

## 项目说明

该仓库包含一个简单的 HTML 页面，用于测试微信 JS-SDK 中的小程序跳转能力。页面会初始化微信 JS-SDK，并在用户点击按钮后尝试跳转到指定小程序页面。

适合用于：

- 学习微信 JS-SDK 基础调用流程
- 验证网页到小程序的跳转链路
- 快速搭建一个静态测试页

## 文件结构

```text
.
├── index.html
└── README.md
```

## 使用方式

直接访问 GitHub Pages 页面，或将 `index.html` 部署到支持 HTTPS 的站点。

需要根据实际项目替换以下配置：

- `appId`
- 小程序页面 `path`
- JS-SDK 签名相关参数

## 注意事项

当前页面是演示代码。正式项目中，`jsapi_ticket` 不应写在前端页面里，签名应由服务端生成后再返回给前端使用。

微信 JS-SDK 的小程序跳转能力通常还需要满足：

- 页面运行在微信客户端环境中
- 域名已在微信公众平台完成 JS 接口安全域名配置
- 使用正确的 `appId`、`timestamp`、`nonceStr` 和 `signature`

## Tech Stack

- HTML
- CSS
- JavaScript
- WeChat JS-SDK

## License

This project is currently provided as a simple demo.
