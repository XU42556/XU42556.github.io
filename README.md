# 阿波次得 · abcd

个人主页，发布在 GitHub Pages 上。

- 线上地址：<https://xu42556.github.io/>
- 页面文件：`index.html`（单文件，样式内嵌，不依赖任何外部资源）

## 怎么改内容

所有内容都在 `index.html` 里，用文本编辑器打开就能改：

| 想改什么 | 在 `index.html` 里找 |
| --- | --- |
| 大标题名字 | `<h1 class="fade">阿波次得</h1>` |
| 身份/状态 | `abcd · Student / 学生` |
| 中文简介 | `<p class="bio-cn fade">…</p>` |
| 英文简介 | `<p class="bio-en fade">…</p>` |
| 链接按钮 | `<nav class="links fade">` 里的 `<a class="btn">` |
| 头像 | 替换本目录里的 `avatar.jpg`（正方形，≥ 400×400） |

改完保存，然后在仓库目录里执行：

```bash
git add -A
git commit -m "update: 修改文案"
git push
```

## 项目展示区

`index.html` 里预留了一段被注释掉的「项目 / Projects」区块，
去掉注释、填上项目名称和链接就能用。

---

© 阿波次得 · Hosted on GitHub Pages
