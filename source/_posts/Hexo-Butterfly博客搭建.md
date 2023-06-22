---
title: Hexo-Butterfly博客搭建
categories: frontend
---

## Hexo搭建注意事项

### git相关

- 关于git部署的域名选择：与自己的githubID保持一致
- 关于`hexo d`命令出现的无法账号密码登陆问题：修改_config.yml文件以下内容(目前看来需要定期换token，后续考虑使用ssh或者服务器)：
```yaml
deploy:
  type: git
  repo: https://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@github.com/Chtholly-Tree/Chtholly-Tree.github.io.git
  branch: master
```

### hexo相关命令

- 创建新博客
```bash
$ hexo new "My New Post"
```

- 在本地服务器运行
```bash
$ hexo server
```

- 生成博客
```bash
$ hexo generate
```

- 部署到git page上
```bash
$ hexo d
```

## Butterfly主题设置
