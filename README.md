# 友班的博客

这是Uband友班的官方博客。

官方博客主要分享优质文章和内容，首先是友班的产品更新、发展新闻、团队建设，其次是技术博客。

发布流程：

- 初稿，提交 pull request
- 评审，需要经过至少 2 人的评审，并给出意见

- 修改，提交 pull request
- 由团队评审会通过过后，放可以发布

## 以下是技术参数

### 修改主题

主题来自 hexo 主题库中的 `Hacker` 主题，尊重原主题作者的版权，在更换我们自己的主题之前，都在博客的底部放置作者本人的 github 项目地址。

修改后请打包为 Harker.zip.

### 发布文章

发布文章只需要在 source/_posts 下发布自己的文章.

格式请参考 [hexo的格式规范](https://hexo.io/docs/writing.html).

### 如何在本地跑起来

确保你的电脑安装了git

```
git clone https://github.com/guoylyy/uband-blog.git

cd uband-blog
```


三条命令就可以让这个博客在本地跑起来

```
npm install hexo -g
npm install
hexo server
```


