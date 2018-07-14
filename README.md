# blog-source
my blog source code
## 博客源码拉取
1. 在本地欲拉取源码的位置 `git clone https://github.com/mingxing47/blog-source.git` 拉取源码；
2. 源码拉取之后 `cd themes`, 然后拉取主题源码 `git clone https://github.com/mingxing47/blog-next-source.git`；
3. 到博客主目录下，更新 `npm` 包，`npm install`；
## 写文章
1. 可以先写草稿 `hexo new draft <filename>`；
2. 然后发布草稿 `hexo p <filename>`；
3. 也可以直接生成文章 `hexo new <filename>`
4. 然后生成文章并发布部署到 `github\coding`，`hexo g -d`；
## 提交博客源码到 `github`
1. `git add .`；
2. `git commit -m "update"`；
3. `git push origing master`
## 其他
主题文件夹里 `_config.yml` 配置文件里，因为评论接口 id 等有隐私性，故没有上传到 `github`，拉取源码下来之后需要把 `_config.yml.bak` 修改为 `_config.yml`，然后再配置相应的内容。