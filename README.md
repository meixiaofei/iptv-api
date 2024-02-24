# TVbox电视直播源接口自动爬取更新

根据基础配置直播源文件获取最新直播源接口链接

## 特点

- 可定时执行，每隔12小时执行更新一次
- 可设置重点关注频道，获取更多直播链接（数量可设置）或速度排序（可选）

## 使用方法

1. Fork此项目，开启Action工作流可读写权限
2. 修改demo.txt文件，后续更新根据此文件内容进行更新
3. 修改main.py(可选)：importantList（关注频道），importantUrlsNum（更新关注频道的源数量）
4. result.txt为更新后的直播源文件，source.json为数据源文件