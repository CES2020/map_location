# map_location
Map_Location是一个地名查询经纬度 | 地址批量转换经纬度工具，这个文档介绍了使用这个工具前后数据处理的流程
根据地名获得经纬度所使用的网站是https://maplocation.sjfkai.com/，需要翻墙
考虑到简化的地名可能在全国范围内存在重复，有必要对地名修改，得到冗余的但是指向更明确的地名。
得到经纬度坐标后，由于应用的需要，进一步处理成特定格式的json文件。
数据处理流程为place_dup.csv--->place_dup_preprocess.xlsx, 在线查询, map-location.xlsx--->map-location3.xlsx--->data.json
详细步骤见“改地址步骤.docx”

