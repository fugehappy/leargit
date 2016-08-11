# 创建Github Pages

gh-pages分支用于构建和发布

访问[网站](https://fugehappy.github.io/leargit/)

创建项目站点步骤：

```bash
$ git clone https://github.com/USERNAME/PROJECT.git PROJECT

$ git checkout --orphan gh-pages

$ git rm -rf .

$ git add .

$ git commit -a -m "First pages commit"

$ git push origin gh-pages
```
