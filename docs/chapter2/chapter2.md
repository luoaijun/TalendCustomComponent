## mcp_connection

> 自定以组件使用请参考：[QuickStart](chapter3/chapter3.md)

### how to use mcp ?
#### Get mcp Jar

- Install 

```
maven install com.servier.mcp
```


- pom 

```
<dependency>
    <groupId>com.servier</groupId>
    <artifactId>mcp</artifactId>
    <version>1.2</version>
</dependency>
```

#### Run graph

- param: 配置参数
- data：数据，如果data为空，则mcp将从mongo直接获取数据
```
com.servier.Graph.run(params,data)
```


### params参数：
- tableMappingName = "Organization"; tableMappingName
- db_name = "DEEPSEA"; mongo connection
- db_port = "27017";mongo 端口
- db_collection = "transactions.records";mongo表
- tokenID = "xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx";32位hashcode
- recodeCode = "HR";
- country = "CN";国家代码
- url_host = "127.0.0.0:8080";接口地址
- db_host = "localhost";mongo数据库地址
- mongo_query = "{sheetName:'Organization'}";mongo查询语句
### 组件参数列表
![运行](resources/images/img.PNG? "参数")
### 运行效果
![效果](resources/images/img2.PNG? "效果")