# lgqm_spider

 临高启明 同人小说 爬取软件

 2019.8.20 本项目改变，改为一个爬虫代码集合项目

[TOC]

# 开发路线图
主版本以LS为前缀。
| 版本      | 简述                       | 发布日期       | 备注   |
| --------- | -------------------------- | -------------- | ------ |
| LS001     | 灰机网站 同人作品下载        |      | 计划2019年6月底开发完成 |

# 程序结构说明
## package 说明
- wdbd.lgqm 主包
  - tools 工具函数包
  - spider 爬虫程序包
- wdbd.spider.xmly 喜马拉雅爬虫代码包
- wdbd.spider.lpr 市场贷款利率爬取代码包


## 依赖包：
在标准的Anaconda3环境下，还需要：
- requests
- pypinyin