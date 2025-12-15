---
title: "使用 Hugo 搭建个人博客"
date: 2025-12-15T20:00:00+08:00
draft: false
tags: ["Hugo", "Blog", "Tutorial"]
series: ["Guide"]
featured: true
---

## 为什么选择 Hugo？

- **速度极快**：Hugo 是用 Go 语言编写的，生成网站的速度非常快。
- **安装简单**：无需复杂的依赖，通常只是一个二进制文件。
- **灵活强大**：拥有丰富的主题和强大的模板系统。
- **Markdown 支持**：专注于写作，使用 Markdown 格式编写内容。

上面是AI写的。我随便选的

## 第一步：安装 Hugo

### macOS 用户

如果你使用 Homebrew，可以直接运行：

```bash
brew install hugo
```

### Windows 用户

可以使用 Chocolatey 安装：

```powershell
choco install hugo -confirm
```

或者直接从 [Hugo Releases](https://github.com/gohugoio/hugo/releases) 页面下载对应的压缩包，解压后将 `hugo.exe` 添加到环境变量中。

验证安装：

```bash
hugo version
```

## 第二步：创建新站点

在终端中运行以下命令来创建一个新的 Hugo 站点：

```bash
hugo new site my-blog
cd my-blog
```

这将创建一个名为 `my-blog` 的文件夹，其中包含 Hugo 站点的基本结构。

## 第三步：添加主题

Hugo 拥有丰富的主题生态。这里我们以 `hugo-theme-ladder` 为例：

```bash
git init
git submodule add https://github.com/guangzhengli/hugo-theme-ladder themes/hugo-theme-ladder
```

然后在 `hugo.toml` (或 `hugo.yaml`) 中启用主题：

```yaml
theme: hugo-theme-ladder
```

## 第四步：创建第一篇文章

使用 Hugo 命令创建新内容：

```bash
hugo new content/post/hello-world.md
```

编辑 `content/post/hello-world.md` 文件，在 front matter (头部元数据) 下方添加你的 Markdown 内容：

```markdown
---
title: "Hello World"
date: 2025-12-15T21:00:00+08:00
draft: false
---

这是我的第一篇博客文章！
```

## 第五步：本地预览

启动 Hugo 内置服务器进行预览：

```bash
hugo server
```

打开浏览器访问 `http://localhost:1313`，你就能看到你的博客了！

## 结语

恭喜你！你已经成功搭建了一个基于 Hugo 的个人博客。接下来，你可以继续探索更多 Hugo 的功能，定制你的主题，开始你的写作之旅。

Happy Coding!
