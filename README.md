## 开发

```bash
# 安装nodejs，建议安装16版本
https://nodejs.org/download/release/v16.20.1/node-v16.20.1-win-x64.zip

# 查看npm配置的镜像仓库
npm config get registry

# 配置为国内的镜像仓库
npm config set registry https://registry.npmmirror.com

# 安装依赖
npm install

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