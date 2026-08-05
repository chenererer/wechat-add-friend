# 微信添加好友链接

点此访问：https://chenererer.github.io/wechat-add-friend/

## 部署步骤（只需做一次）

### 1. 生成页面
```bash
python main.py
# 修改 main.py 底部 wechat_id 为你的微信号后再运行
```

### 2. 上传到 GitHub

把 `output/index.html` 文件上传到仓库 **根目录**（不要放在 output 文件夹里），结构如下：

```
wechat-add-friend/
└── index.html    ← 就这一个文件放在根目录
```

### 3. 开启 GitHub Pages

仓库 → Settings → Pages →
- Source: `Deploy from a branch`
- Branch: `main`，文件夹选 `/ (root)`
- 点 Save，等 1-2 分钟

### 4. 访问

https://chenererer.github.io/wechat-add-friend/
