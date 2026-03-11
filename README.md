# Image Gallery

GitHub Pages + SMMS 混合存储图片画廊

## 存储策略

- **最新图片（本月）** → GitHub 仓库（2GB 限额）
- **稍早图片（1-2月前）** → SMMS 图床（5GB/月）
- **更早图片** → 本地归档

## 文件结构

```
├── index.html      # 画廊主页
├── images.json     # 图片数据（日期、URL、存储位置）
└── images/         # GitHub 存储的图片
    └── 2026-03-11/
        └── xxx.png
```

## 访问地址

https://hectoeleebanana-arch.github.io/image-gallery/