# 个人博客

基于 [Jekyll](https://jekyllrb.com/) 与 GitHub Pages 构建的个人博客。早期版本参考并修改了 [jekyll-theme-solid](https://mazhuang.org/jekyll-theme-solid/) 模板，感谢原作者。

## 内容与状态

仓库保存了个人文章、学习笔记和 Jekyll 站点文件。主要文章发表于 2023 年；当前作为历史学习记录保留，不代表持续维护中的产品。

## 技术栈

- Ruby、Jekyll
- GitHub Pages
- Gemfile 声明了 `github-pages` 与 `webrick`

仓库没有 `Gemfile.lock`，依赖解析结果可能随时间变化。评论系统配置保留了模板默认值；如需启用评论，应先替换为自己的设置，并避免把私密凭据写入公开配置。

## 本地预览

需要已安装的 Ruby 与 Bundler：

```sh
bundle install
bundle exec jekyll serve
```

然后访问终端提示的本地地址。上述步骤尚未在当前环境验证；旧依赖与本地 Ruby 版本可能需要进一步调整。

## 来源与限制

站点基于上述模板修改，仓库包含 LICENSE 文件。请同时查看模板和仓库许可条款。旧文章和评论配置可能包含过时信息，发布或重新启用功能前请先检查。
