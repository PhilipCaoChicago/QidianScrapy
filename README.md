# 起点小说网爬虫

该爬虫使用Scrapy框架，目前还没有添加IP池和布隆过滤器。

## 注意事项

1. 使用前请确定Mongodb已安装并打开。
2. 因为起点书城“全部”分类下的书籍在5000页之后就无法爬去爬取，所以本爬虫采用了抓取所有细分分类的页面后再次抓取细分页面的不同页。

## 使用方法
请直接运行

```
scrapy crawl qidian
```



