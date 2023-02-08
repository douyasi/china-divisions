中国（大陆）县级以上行政区划数据库
-----

>   本项目由 [douyasi/identity-card](https://github.com/douyasi/identity-card) 剥离析出，以减少该包的大小及其特定语言依赖，未来本仓库将专注于行政区划数据爬虫与归档 —— 提供多种格式（如 `text/csv/js/sqlite/sql`）等数据源文件，以方便其它语言调用。

### 基于本数据库实现的项目

- 中国（大陆）身份证号码校验类库 [douyasi/identity-card](https://github.com/douyasi/identity-card) 及其衍生版本： [Node/Javascript 实现版本](https://github.com/ycrao/id.js) 、[Rust 实现版本](https://github.com/ycrao/idrs)
- 省市县三级联动地址效果见此 [在线网页](https://raoyc.com/address-selector/) ，地区相关的js数据在 [此](https://raoyc.com/address-selector/divisions.js) ，文件大小约 `99KB` 。


### 数据爬虫

请参考 `crawler` 目录下 [`readme`](crawler/readme.md) 文件。

### 版本、更新与反馈

请参考 `db` 目录下 [`readme`](db/readme.md) 文件。

### 数据源文件

最新的（多格式）数据源文件位于 `dist/2021` 目录下，采集截止到 2021年 的最新数据，来自于民政部网站。

### 参考资源

- 中华人民共和国国家统计局 [行政区划代码](http://www.stats.gov.cn/tjsj/tjbz/tjyqhdmhcxhfdm/)
- 民政部 [县级以上行政区划变更情况](http://xzqh.mca.gov.cn/description?dcpid=1)
- 民政部 [中华人民共和国行政区划代码](https://www.mca.gov.cn/article/sj/xzqh/1980/)