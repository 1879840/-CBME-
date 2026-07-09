# 豌豆思维 CBME 闯关体验

豌豆思维十周年·思维成长看得见

在线体验：[点击访问](https://你的域名.vercel.app)

## 部署到 Vercel

已准备好部署文件，按以下步骤操作：

### 方式一：通过 Vercel 网站部署（推荐，最简单）

1. **访问 Vercel**  
   打开 [vercel.com](https://vercel.com)，点击右上角 "Sign Up" 或 "Log In"

2. **使用 GitHub 登录**  
   选择 "Continue with GitHub"，授权 Vercel 访问你的 GitHub 账号

3. **导入项目**  
   - 点击 "Add New..." → "Project"
   - 点击 "Import Git Repository"
   - 如果还没有仓库，先去 GitHub 创建一个新仓库，将当前展会文件夹的文件上传上去
   - 在 Vercel 中找到该仓库并点击 "Import"

4. **配置项目（保持默认即可）**  
   - Project Name: `wandou-cbme-h5`（可自定义）
   - Framework Preset: 选择 "Other"
   - Root Directory: `./`
   - 其他保持默认

5. **点击 Deploy**  
   等待约 30 秒，部署完成！

6. **获取链接**  
   部署成功后会显示：`https://wandou-cbme-h5.vercel.app`（或你自定义的域名）

---

### 方式二：通过命令行部署（需要命令行工具）

如果你熟悉命令行，可以使用 Vercel CLI：

```bash
# 安装 Vercel CLI
npm i -g vercel

# 在项目目录执行
cd /Users/xiaoke/Documents/claude-workspace/展会
vercel

# 按提示登录并部署
```

---

## 生成二维码

部署完成后，将得到的链接（如 `https://wandou-cbme-h5.vercel.app`）：

1. **方式一：草料二维码**  
   访问 [cli.im](https://cli.im/)，粘贴链接生成二维码

2. **方式二：微信自带**  
   将链接发送给自己，长按链接 → 提取二维码

3. **方式三：在线工具**  
   [qr.ioi.tw](https://qr.ioi.tw/) 或 [qrcode.show](https://qrcode.show/)

---

## 注意事项

- Vercel 提供免费 SSL 证书（HTTPS）
- 全球 CDN 加速，访问速度快
- 支持自定义域名（可选）
- 每次推送代码到 GitHub，Vercel 会自动重新部署

---

## 需要帮助？

如果在部署过程中遇到问题，可以：
1. 查看 [Vercel 官方文档](https://vercel.com/docs)
2. 后台回复"部署"获取一对一支持
