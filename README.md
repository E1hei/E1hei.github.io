# YiFan Wang — Personal homepage

个人主页：https://e1hei.github.io/

页面为独立的 `index.html`，不需要安装依赖或执行构建。

## 如何修改

1. 打开 https://github.com/E1hei/E1hei.github.io 。
2. 点击 `index.html`，再点击铅笔图标编辑。
3. 搜索要修改的姓名、邮箱或介绍并修改。修改邮箱时，同时更新可见文字和 `mailto:` 链接。
4. 点击 **Commit changes** 保存。GitHub Pages 会自动更新，发布可能需要几分钟。

## 首次配置 GitHub Pages

在仓库 **Settings → Pages → Build and deployment** 中设置：

- **Source:** Deploy from a branch
- **Branch:** main
- **Folder:** / (root)

## 本地预览

在本目录运行：

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

然后打开 http://127.0.0.1:8765/ 。

## 参考

- https://docs.github.com/en/pages/quickstart
