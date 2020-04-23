# 产品介绍
CODING Devops 与腾讯云 Serverless Framework 合作共同打造从需求计划、编码、测试、构建、发布部署、运营监控一站式解决方案。开发者可以借助 腾讯云、CODING、serverless 资源，只需专注业务逻辑即可迅速创建 web 应用。本手册用于引导读者使用 CODING Devops 工具和腾讯云资源创建、管理 Serverless 全栈 WEB 应用（Vue.js）应用；

# 产品功能
#### 一站式服务
体验从**计划** -> **编码** -> **构建** -> **测试** -> **发布** -> **部署** -> **运营** -> **监控** Devops 全流程

![图片](https://static-serverless-coding-1255529448.cos.ap-shenzhen-fsi.myqcloud.com/devops.jpg)

#### 极速创建全栈应用
支持开发者在一分钟内创建 Serverless Framework 应用

#### 可调度多方资源
开发者可以同时使用 Coding、腾讯云、Serverless 多方提供的资源构建应用

# 快速入门

## 使用场景

### 在 Coding 中使用 **Serverless 全栈 WEB 应用（Vue.js）**

你可以通过如下两种方式在在 Coding 上体验 Servlerss Component

- 新建/重置示例项目

- 创建范例项目

1、在 Coding 上注册新团队，系统会默认初始化仓库内容为 **Serverless 全栈 WEB 应用（Vue.js）** 的 **Serverless Component 示例项目**

![图片](https://static-serverless-coding-1255529448.cos.ap-shenzhen-fsi.myqcloud.com/1%E3%80%81%E5%9C%A8%20Coding%20%E4%B8%8A%E4%BD%BF%E7%94%A8%20Serverless%20Demo%20%7C%20%E7%A4%BA%E4%BE%8B%E9%A1%B9%E7%9B%AE.png)

如果你的团队**示例项目**源码非 Serverless Component，请尝试重置项目

![图片](https://static-serverless-coding-1255529448.cos.ap-shenzhen-fsi.myqcloud.com/1%E3%80%81%E5%9C%A8%20Coding%20%E4%B8%8A%E4%BD%BF%E7%94%A8%20Serverless%20Demo%20%7C%20%E9%87%8D%E7%BD%AE%E7%A4%BA%E4%BE%8B%E9%A1%B9%E7%9B%AE.png)

2、创建新范例项目时，用户可以选择 **Serverless 全栈 WEB 应用（Vue.js）**模版，初始化你的 **Serverless Component 项目**

![图片](https://static-serverless-coding-1255529448.cos.ap-shenzhen-fsi.myqcloud.com/2%E3%80%81%E5%9C%A8%20Coding%20%E4%B8%8A%E4%BD%BF%E7%94%A8%20Serverless%20Demo%20%7C%20%E6%96%B0%E5%BB%BA%E8%8C%83%E4%BE%8B%E9%A1%B9%E7%9B%AE1.png)

创建项目时需要进行腾讯云授权，目前支持「扫码临时授权」和「云 API 密钥授权」，权限及云 API 秘钥的配置可以参考[配置文档](https://cloud.tencent.com/document/product/1154/43006)。

![图片](https://static-serverless-coding-1255529448.cos.ap-shenzhen-fsi.myqcloud.com/2%E3%80%81%E5%9C%A8%20Coding%20%E4%B8%8A%E4%BD%BF%E7%94%A8%20Serverless%20Demo%20%7C%20%E6%96%B0%E5%BB%BA%E8%8C%83%E4%BE%8B%E9%A1%B9%E7%9B%AE2.png)


3、**Serverless Component 项目**初始化完成后，CODING Devops 提供自动构建能力，流程配置默认使用 仓库源码中 Jenkinsfile；如果你想自定义你的 **Serverless Component 项目**自动构建配置，请修改 Jenkinsfile 或者构建计划中的配置
 
![图片](https://static-serverless-coding-1255529448.cos.ap-shenzhen-fsi.myqcloud.com/3%E3%80%81%E5%9C%A8%20Coding%20%E4%B8%8A%E6%9E%84%E5%BB%BA%20Serverless%20framework.png)


4、自动构建成功后，查看项目公告获取发布后的你的应用访问地址

![图片](https://static-serverless-coding-1255529448.cos.ap-shenzhen-fsi.myqcloud.com/3%E3%80%81%E5%9C%A8%20Coding%20%E4%B8%8A%E6%9E%84%E5%BB%BA%E7%BB%93%E6%9E%9C-%E5%AF%B9%E5%A4%96%E9%93%BE%E6%8E%A5.png)


### 在 Cloud Studio 中使用 Serverless Framework - Serverless Demo

> Cloud Studio 内部封装了安装环境，下载依赖，调用腾讯云资源等功能，仅对用户暴露图形化操作界面创建应用

Cloud Studio 内部集成了 **Serverless Component**，支持一键生成运行在云端的 **Serverless Component 示例项目**。访问 [Cloud Studio](https://cloudstudio.net/)，选择新建「新建工作空间」 -> 「Serverless Framework」环境 -> 「Serverless Demo」即可初始化你的全站项目

![图片](https://static-serverless-coding-1255529448.cos.ap-shenzhen-fsi.myqcloud.com/1%E3%80%81%E5%9C%A8%20VS%20%E4%B8%8A%E4%BD%BF%E7%94%A8%20Serverless%20Demo%20%7C%20%E4%BA%A7%E5%93%81%E5%85%A5%E5%8F%A3a.png)


![图片](https://static-serverless-coding-1255529448.cos.ap-shenzhen-fsi.myqcloud.com/1%E3%80%81%E5%9C%A8%20VS%20%E4%B8%8A%E4%BD%BF%E7%94%A8%20Serverless%20Demo%20%7C%20%E4%BA%A7%E5%93%81%E5%85%A5%E5%8F%A3b.png)


![图片](https://static-serverless-coding-1255529448.cos.ap-shenzhen-fsi.myqcloud.com/1%E3%80%81%E5%9C%A8%20VS%20%E4%B8%8A%E4%BD%BF%E7%94%A8%20Serverless%20Demo%20%7C%20%E8%BF%90%E8%A1%8C%20Demo.png)

Serverless Component 简介及命令行支持请参考 [Github 项目说明](https://github.com/serverless/components/blob/master/README.cn.md)。

### 使用腾讯云资源

当前 Full Stack 项目使用如下云服务：

- [x] **API 网关** - API 网关将会接收外部请求并且转发到 SCF 云函数中。
- [x] **SCF 云函数** - 云函数将承载 Express.js 应用。
- [x] **CAM 访问控制** - 该组件会创建默认 CAM 角色用于授权访问关联资源。
- [x] **COS 对象存储** - 为确保上传速度和质量，云函数压缩并上传代码时，会默认将代码包存储在特定命名的 COS 桶中。此外，会通过 COS bucket 支持静态资源的托管。

如果希望查看部署完成的 Serverless 应用和状态信息，可以通过 [Serverless Framework 控制台](https://serverless.cloud.tencent.com/) 进行查看和管理。 

# 常见问题

#### 1. 从 Coding 上拉取 **Serverless 全栈 WEB 应用（Vue.js）** 源码，无法正常运行，请参照仓库 README.md 在项目资源下配置 .env 文件；


#### 2. Serverless Framework 报错“The appid is unavailable for legal reasons.” 如何处理？

该报错是由于账户欠费，无法创建新的后付费资源所导致的。请您检查账户是否欠费，账户冲正后即可解决。

#### 3. 遇到“Cannot get secretId/Key, your account could be sub-account or does not have access”报错如何处理？
问题描述：完整的报错内容为 “ Cannot get secretId/Key, your account could be sub-account or does not have access, please check if SLS_QcsRole role exists in your account, and visit https://console.cloud.tencent.com/cam to bind this role to your account.” 

解决方法：该报错为账户权限不足，可以参考 [账号和权限配置](https://cloud.tencent.com/document/product/1154/43006) 进行配置更新。


更多的问题和反馈，可以参考 [Github 仓库 Issues](https://github.com/serverless-components?q=tencent)。



