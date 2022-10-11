# 访问地址
https://potato.gold/navbar/tool/shiro/ShiroTool.html

# 主要功能
内置100多个key，爆破解密rememberMe加密字段内容，对解密内容进行反序列化，展示反序列化后字节流。

根据序列化协议，逐字节读取解析，进行对象结构化展示，ysoserial CommonsBeanutils CommonsCollections等payload都能识别。

对涉及class文件的，再进行class反编译出java代码。

![image](/img/main.png)

## 一、字节流展示：
![image](/img/1.png)

## 二、对象结构化展示：
![image](/img/2.png)

## 三、反编译展示：
![image](/img/3.png)