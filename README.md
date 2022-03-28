<!--
 * @Author: your name
 * @Date: 2022-03-27 16:10:58
 * @LastEditTime: 2022-03-28 11:25:43
 * @LastEditors: your name
 * @Description: 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
 * @FilePath: \zs-pc-front-templete\README.md
-->

## 开发

```bash

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装依赖，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

浏览器访问 http://localhost:80

## 发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```

## 依赖

本地安装 ApiPost, 登陆邮箱发给gaomeng添加权限，用于前端mock数据。
