# BlogImages

公众号/博客文章图床，通过 [PicGo](https://picgo.github.io/PicGo-Doc/) 上传管理。

## 目录结构

```
BlogImages/
├── android/       # Android 技术类
├── tech/          # 其他技术类
├── blockchain/    # 区块链
├── life/          # 个人/杂谈
└── README.md
```

每篇文章的图片存放在对应分类下，文件夹命名格式：`YYYY-MM-DD-文章标题简称/`

## PicGo 配置

| 配置项 | 值 |
|--------|-----|
| 仓库 | `visiongem/BlogImages` |
| 分支 | `master` |
| 自定义域名 | `https://cdn.jsdelivr.net/gh/visiongem/BlogImages@master` |

## CDN 访问

图片上传后，通过 jsDelivr CDN 访问：

```
https://cdn.jsdelivr.net/gh/visiongem/BlogImages@master/分类/文章文件夹/图片名
```

示例：

```
https://cdn.jsdelivr.net/gh/visiongem/BlogImages@master/android/2026-06-01-compose-tips/screenshot.png
```
