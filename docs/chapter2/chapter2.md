## AiPool-GDC

> 自定以组件使用请参考：[QuickStart](chapter3/chapter3.md)

```
来自公司项目MCP CLOUDER
```

- 设计模式
- 功能介绍
- 应用场景
- 错误提示与解决建议

### 引用

#### Technology-package

> [Push Your JAR to maven center](https://luoaijun.github.io/note-book/#/chapter4/chapter4)

##### Repository：mcp 
1. [mcp quick-start](https://luoaijun.github.io/com.cdes.custom.talend/#/chapter2/chapter2)
2. [source code](https://github.com/luoaijun/MCPUtils)


- Install 
```
mvn install com.luoaijun.mcp
```


- pom 
```
<dependency>
    <groupId>com.luoaijun</groupId>
    <artifactId>mcp</artifactId>
    <version>1.2</version>
</dependency>
```
- [download jar](https://repo1.maven.org/maven2/com/luoaijun/mcp/mcp/1.2/mcp-1.2.jar) 


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