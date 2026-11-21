# 我的小站

一个单文件、离线可用的手机/电脑网页。所有内容都在 `index.html` 顶部的 `CONTENT` 对象里。

## 部署到 GitHub Pages（一次性）

1. 打开 https://github.com/signup 注册账号（邮箱 + 用户名 + 密码，邮箱收验证码）。
2. 打开 https://github.com/new 新建仓库：
   - Repository name 填 `mysite`
   - 可见性选 **Public**（Pages 免费版要求公开仓库）
   - 不要勾选 README
   - 点 **Create repository**
3. 在仓库页面点 **Add file → Upload files**，把本目录的 `index.html` 和 `README.md` 拖进去，点 **Commit changes**。
4. 进入 **Settings → Pages**：
   - Source 选 **Deploy from a branch**
   - Branch 选 `main`，目录选 `/ (root)`
   - 点 **Save**
5. 等 1～2 分钟，页面顶部会出现网址：`https://<你的用户名>.github.io/mysite/`
6. 电脑和手机都打开这个网址即可；手机上用浏览器菜单「添加到主屏幕」。

## 后续更新内容

改完 `index.html` 后：

1. 打开仓库页面 → **Add file → Upload files**
2. 重新拖入新的 `index.html`，覆盖同名文件
3. **Commit changes**，等 1 分钟左右刷新即可看到

## 注意

- 仓库是公开的，**不要把密码、身份证、家庭住址等敏感信息写进页面**。
- Pages 地址谁拿到都能访问；如需简单遮挡，可以在页面里加一个访问口令（不是真正的安全措施）。
