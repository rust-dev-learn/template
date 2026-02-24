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

## 新建项目

```bash
cargo generate rust-dev-learn/template
```

### 安装pre-commit

pre-commit是一个代码检查工具，可以在提交代码前进行代码检查。

```sh
pip install pre-commit
```

安装成功后，运行`pre-commit install`即可。

### 安装cargo deny工具

cargo deny是一个cargo插件，用于检查依赖的安全性。

```sh
cargo install --locked cargo-deny
```

### 安装typos

typos是一个拼写检查工具。

```sh
cargo install typos-cli
```

### 安装git cliff

git cliff是一个生成changelog的工具。

```sh
cargo install git-cliff
```

### 安装cargo nextest

cargo nextest是一个Rust的增强测试工具。

```sh
cargo install cargo-nextest --locked
```
