# 微信添加好友页面

这个页面可以用来分享微信好友添加链接，对方点击后可唤起微信或扫码添加。

## 在线预览

部署后访问：`https://你的用户名.github.io/wechat-add-friend/add_wechat.html`

## 部署步骤

### 1. 上传到 GitHub

- 创建一个新的 GitHub 仓库，比如叫 `wechat-add-friend`
- 把整个 `output/` 文件夹里的内容上传到仓库根目录

### 2. 开启 GitHub Pages

- 进入仓库 → Settings → Pages
- Source 选择 `Deploy from a branch`
- Branch 选择 `main`，目录选 `/ (root)`
- 点击 Save，等 1-2 分钟即可

### 3. 访问链接

`https://你的用户名.github.io/wechat-add-friend/add_wechat.html`

## 本地生成

```bash
# 修改 main.py 中的微信号后运行
python main.py
```
