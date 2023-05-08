这个分支存储的是生成网页的代码

```bash
mkdir hexo
cd hexo
hexo init
cd ..
git clone -b hexo https://github.com/jeromefan/jeromefan.github.io.git
# 将克隆下来的本仓库中的内容覆盖复制到hexo文件夹中
npm install hexo-deployer-git --save
```

`hexo g` 为生成网页的命令

`hexo d` 为上传网页的命令