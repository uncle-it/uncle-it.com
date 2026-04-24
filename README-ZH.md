[English](README.md)

# 安装 Hugo

Macos (Homebrew)

````bash
brew install hugo
````

Windows (Chocolatey)  推荐使用 extended 版本，支持 SASS/SCSS

```bash
choco install hugo-extended
```

Linux (Debian/Ubuntu)

```bash
sudo apt install hugo
```

查看版本号： (我的版本号: hugo v0.160.1+extended+withdeploy darwin/arm64 BuildDate=2026-04-08T14:02:42Z VendorInfo=Homebrew)

```bash
hugo version 
```

# 创建项目

```bash
hugo new project uncle-it
```

## 创建新的主题

```bash
hugo new theme uncleIt
```

## 运行

```bash
hugo server -D
```

## 新建文章

```bash
hugo new posts/my-first-post.md
```