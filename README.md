# Xiaohongshu-app-crawler
本仓库存储小红书app端任务导向爬虫代码，并未上传全部代码/依赖，如有相同功能需求可联系我

## 功能
可通过抓包顺利爬取某个hashtag下的所有唯一note_id，并根据note_id爬取详细帖子数据，包括文本、图片、视频。

## 流程
<img width="416" alt="image" src="https://github.com/wtwyzc/Xiaohongshu-APP-crawler/assets/117346587/9859f598-f4b8-4855-badc-4383d2ca52e4">


## 建议
- 本代码开发时此平台网页版没有检索功能
- 截止2023.9网页版没有hashtag入口
- 小红书app的帖子显示限制为；
  - 关键词：100条
  - hashtag：1000条

* 因此，如需获取大规模数据，我推荐通过hashtag_id追踪数据。

## 注意
本项目参考了多个不同功能的代码，优化为适应自身任务的程序，具体参考链接找不到了。
如果曾经的贡献者看到可以联系我，谢谢。
