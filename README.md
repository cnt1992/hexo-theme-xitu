![hexo-theme-xitu](https://github.com/cnt1992/hexo-theme-xitu/blob/master/source/img/preview.JPEG)

## 安装

``` bash
hexo init Blog
cd Blog 
npm install
npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
git submodule add https://github.com/cnt1992/hexo-theme-xitu.git themes/xitu
```

## 启用

修改 `_config.yml` 的 `theme` 配置项为 `xitu`:

```yaml
theme: xitu

# 在归档页面显示所有文章
# 需要上面安装的 hexo-generator-archive 插件支持
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## 更新

``` bash
git submodule update
```

## License

MIT