# ars-util
Arsframework util模块采用纯Java语言编写，提供了针对日常处理需要的工具方法，如日期、文档、Excel、JSON、字符串等。

## 1 环境依赖
JDK1.8+

## 2 部署配置
在Maven配置中添加如下依赖：
```
<dependency>
    <groupId>com.arsframework</groupId>
    <artifactId>ars-util</artifactId>
    <version>1.0.5</version>
</dependency>
```

## 3 功能描述
该模块默认包含了对```ars-annotation```的依赖，如果引用该模块，则不用再次引用```ars-annotation```模块。

### 3.1 com.arsframework.util.Dates
该抽象类提供了针对日期处理的工具方法，如日期转换、计算等。

### 3.2 com.arsframework.util.Documents
该抽象类提供了针对文档处理的工具方法，如SVG转PDF、HTML转PDF等。

### 3.3 com.arsframework.util.Excels
该抽象类提供了针对Excel处理的工具方法，如Excel读写。

### 3.4 com.arsframework.util.Files
该抽象类提供了针对文件处理的工具方法，如文件创建、删除、移动、读写、查找塞选等。

### 3.5 com.arsframework.util.Jsons
该抽象类提供了针对JSON处理的工具方法，如对象与JSON之间的相互转换、对象指定深度序列化等。

### 3.6 com.arsframework.util.Nfile
```Nfile```为```Not only file```的缩写，该类为本地文件、字节数组、数据流提供一种中间转换对象，方便程序解耦。

### 3.7 com.arsframework.util.Objects
该抽象类提供了针对对象处理的工具方法，如对象反射操作、对象比较、对象转换等。

### 3.8 com.arsframework.util.Randoms
该抽象类提供了针对随机数处理的工具方法，如随机生成字符串、数字、日期、对象等。

### 3.9 com.arsframework.util.Secrets
该抽象类提供了针对数据加解密处理的工具方法，如MD5加密、DES加解密、AES加解密等。

### 3.10 com.arsframework.util.Streams
该抽象类提供了针对数据流处理的工具方法，如对象序列化与反序列化、数据流读写等。

### 3.11 com.arsframework.util.Strings
该抽象类提供了针对字符串处理的工具方法，如进制转换、匹配、合并、条件转换等。

### 3.12 com.arsframework.util.Webs
该抽象类提供了针对Web应用处理的工具方法，如```Cookie```操作、参数获取、参数转换、视图渲染等。

### 3.13 com.arsframework.util.Asserts
该抽象类提供了断言处理的工具方法，如非Null、非空、大小、长度验证等。

## 4 版本更新日志
### v1.0.4
1. 内部优化
2. 更新```ars-annotation```依赖版本号为```1.3.2```

### v1.0.5
1. 新增```com.arsframework.util.Asserts```断言处理工具类
2. 优化```com.arsframework.util.Excels```处理逻辑
3. 更新```ars-annotation```依赖版本号为```1.4.0```
