# 小说阅读器激活码管理后台

管理后台部署在 Vercel，调用阿里云 FC 的 API。

## 一键部署

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/cooleye/novel-reader-admin)

## 手动部署

```bash
# 克隆仓库
git clone https://github.com/cooleye/novel-reader-admin.git

# 进入目录
cd novel-reader-admin

# 安装 Vercel CLI
npm i -g vercel

# 登录并部署
vercel login
vercel --prod
```

## 配置

在 `index.html` 中修改 API 地址：

```javascript
const API_BASE = 'https://your-fc-url.cn-hangzhou.fcapp.run';
```

## 功能

- 管理员登录
- 生成激活码
- 查看激活码列表
- 查看统计数据

## 技术栈

- 纯 HTML + CSS + JavaScript
- Vercel 静态托管
- 调用阿里云 FC API