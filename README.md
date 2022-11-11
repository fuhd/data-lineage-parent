## data-lineage-parent

> 参考别人的项目，计划在这之上按自己的需求定制化

> 数据血缘，使用各种hook或sql解析，统一将血缘信息存到kafka后，在neo4j中进行储存展现

### 1. lineage-hooks

> 里面有各种hook，实现血缘采集

#### 1.1 lineage-hive-hook

[通过hive hook将血缘信息写入kafka](lineage-hooks/lineage-hive-hook/README.md)

> hive血缘neo4j示例

![image](doc/images/hive_lineage_demo.png)
