# YiFan Wang — Personal homepage

个人主页：https://e1hei.github.io/

页面为独立的 `index.html`，不需要安装依赖或执行构建。

## 当前内容

- 简介：复旦大学大数据学院统计学硕士在读，2025 年入学，预计 2028 年毕业。
- 教育经历：2021–2025 年，复旦大学大数据学院，人工智能（大数据班）；2025 年起，统计学硕士在读。
- 联系方式：公开邮箱和 GitHub 文本链接；已移除 Say hello 按钮及复制邮箱脚本。
- 本科未指定学位类型，页面使用 Undergraduate studies；未补写导师、研究方向、论文或项目。

## 版式与后续内容

采用窄版阅读区、简介优先、时间倒序的教育经历与文本链接。未来可在 Education 后加入 Research、Selected Projects 或 Publications，补充确认后的真实内容。

风格和信息组织参考以下个人主页，未复制他人的履历或正文：

- Jon Barron：https://jonbarron.info/ ，参考简介、联系方式和内容区块的紧凑组织。
- Andrej Karpathy：https://karpathy.ai/ ，参考按时间排列的经历与直接的个人介绍。
- Chip Huyen：https://huyenchip.com/ ，参考以简短正文介绍背景并提供相关链接。

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
