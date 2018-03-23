[中文版](README_cn.md)

<h1 align="center">JAVA SDK For Ontology  </h1>
<h4 align="center">Version V0.6.0 </h4>

## 总体介绍

The project is an ontology official Java SDK, which is a comprehensive SDK. Currently, it supports local wallet management, digital identity management, digital asset management,  deployment and envoke for Smart Contract , and communication with Ontology Blockchain. The future will also support more rich functions and applications .

## 开始使用

进入[新手指南](docs/en/api_desc.md)开始使用。

## 如何安装

### 环境准备

请配置JRE 8及以上版本。

> **Note:** 由于SDK中使用的密钥长度大于128，由于安全策略文件受限的原因，需要去官网下载local_policy.jar和US_export_policy.jar，替换jre目录中${java_home}/jre/lib/security原有的与安全策略这两个jar即可。

下载地址：
>http://www.oracle.com/technetwork/java/javase/downloads/jce8-download-2133166.html


### 编译

```
mvn clean install
```

### 运行前准备

* 请确定Ontology Blockchain已经部署OK，其RPC端口已经打开，SDK将此连接地址作为URL参数进行初始化参数。

* 请确定本地钱包的存储路径，钱包用于存储数字身份信息和数字资产相关的密钥控制信息，可以文件形式，也可以是数据库形式。



