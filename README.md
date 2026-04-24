[简体中文](README-ZH.md)



# Install

Macos (Homebrew)

````bash
brew install hugo
````

Windows (Chocolatey) [The extended version is recommended, as it supports SASS/SCSS]

```bash
choco install hugo-extended
```

Linux (Debian/Ubuntu)

```bash
sudo apt install hugo
```

View version (My version: hugo v0.160.1+extended+withdeploy darwin/arm64 BuildDate=2026-04-08T14:02:42Z VendorInfo=Homebrew)

```bash
hugo version 
```

## Create Project

```bash
hugo new project uncle-it
```

## Create new theme

```bash
hugo new theme uncleIt
```

## Run dev

```bash
hugo server -D
```

## New post

```bash
hugo new posts/my-first-post.md
```