# Rust项目工程模版

## 提交初始化项目

```bash
git init
pre-commit install
git commit -a
```

## VSCode 插件介绍

- crates: Rust 包管理
- Even Better TOML: TOML 文件支持
- Better Comments: 优化注释显示
- Error Lens: 错误提示优化
- GitLens: Git 增强
- Github Copilot: 代码提示
- indent-rainbow: 缩进显示优化
- Prettier - Code formatter: 代码格式化
- REST client: REST API 调试
- rust-analyzer: Rust 语言支持
- Rust Test lens: Rust 测试支持
- Rust Test Explorer: Rust 测试概览
- TODO Highlight: TODO 高亮
- vscode-icons: 图标优化
- YAML: YAML 文件支持

## 安装cargo generate

cargo generate是一个用于生成项目模版的工具。它可以使用已有的github repo作为模版，生成新的项目。

```sh
cargo install cargo-generate
```