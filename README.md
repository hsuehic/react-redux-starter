# React Redux application starter

## 安装
* nodejs
* gitbook
```blash
npm i -g gitbook
```
* 安装项目依赖
在项目根目录下执行
```blash
npm i
```

## 开发前准备
开发前请阅读[文档](https://hsuehic.gitbooks.io/react-rudex-starter/content/)。

## 目录结构说明

```bash
├── package.json      # Dependencies and Scripts
├── README.md         # This file
├── index.html        # Page Template
├── config/           # Config files
├── docs/             # Documents
├── scripts/          # Build Scripts
└── src/              # All source code
    ├── actions/      # Font files
    ├── assets/       # Images and SVGs
    ├── components/   # Javascript libraries and scripts
    ├── partials/     # Handlebars HTML partials that are included / extended
    ├── sass/         # Stylesheets
    └── templates/    # Handlebars HTML files, one per page on the site. 
└── test/             # Build Scripts
    ├── actions/      # Font files
    ├── components/   # Font files
    └── reducers/     # Handlebars HTML files, one per page on the site.

```

## 开发调试

### 开发
 在项目根目录下执行
  ```blash
  npm run start
  ```

### API文档
  ```blash
  gitbook serve
  ```

### 生成发布 
```blash
npm run build
```