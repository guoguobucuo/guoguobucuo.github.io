# 个人博客部署说明

## 1) 本地访问

在项目根目录执行：

```powershell
python -m http.server 8080
```

浏览器打开：

`http://localhost:8080`

## 2) 发布到 GitHub Pages

1. 在 GitHub 新建仓库（建议仓库名：`<你的用户名>.github.io`）。
2. 把当前目录代码推送到该仓库的 `main` 分支。
3. 进入仓库设置：`Settings -> Pages`。
4. 在 `Build and deployment` 中选择：
   - `Source: Deploy from a branch`
   - `Branch: main`
   - `Folder: / (root)`
5. 保存后等待 1-3 分钟，访问：
   - `https://<你的用户名>.github.io/`

## 3) 你可以优先替换的个性化信息

- `index.html` 中站点名：`AIGC Creator Blog`
- `index.html` 中邮箱：`you@example.com`
- `index.html` 中 GitHub 链接：`https://github.com/`
- `posts/*.html` 中作者信息（当前保留了模板作者字段）


