<p align="center">
<img src="https://github.com/user-attachments/assets/9cb01354-0b57-4dfe-acad-30638b24101d" alt="APKHunt"/>
</p>

<hr/>

# “铲子”SAST工具介绍

### 一、产品定位

* “铲子”是一款简单易用的JAVA SAST（静态应用程序安全测试）工具，旨在为安全工程师提供一款**简单、好用、价格厚道**的代码安全扫描产品。
* 官网：[www.chanzikeji.com](https://www.chanzikeji.com)

### 二、功能介绍

* 支持语言: java（Servlet&Filter、Spring、Dubbo、Thrift、JFinal、Netty、Struts2、JAX-WS（含 CXF 等实现）、JAX-RS（含 Jersey、Dropwizard 等实现）、MyBatis、JDK HttpServer、JSP、XML、YAML、Properties、Maven POM、Gradle、JBoot、JSF、solon、motan）
* 采用技术：污点分析，铲子会将java、xml（mybatis、dubbo）等统一构建数据流图，无需编译，然后进行污点分析，漏洞结果可在数据流窗口进行方便的阅读
* 支持漏洞：内置了 sql 注入、命令注入、文件上传、ssrf、xss、水平越权 等常见cwe漏洞规则，以及log4j、shiro、xstream、actuator、xxljob、Struts、springgateway等组件类漏洞规则
* 导出报告：用户可对漏洞进行标记，并导出简洁清晰的漏洞报告，包括漏洞统计、漏洞类型、危害等级、数据流、漏洞位置以及修复建议，帮助开发人员快速定位和解决问题
* 反编译:支持反编译扫描，可以在新建任务时选择需要反编译的jar或class文件，也可以在审计过程中对单个class或jar文件进行反编译阅读代码
* 编辑器：多功能代码编辑器，为了更方便的阅读代码，减少用户在sast工具及ide之前频繁切换，铲子内置了 lsp 服务器，支持类型、变量、方法的跳转及使用查找，支持快速搜索全仓库，及文件的代码大纲
* 自定义规则：自定义规则采用cypher查询语言，用户学习门槛低，对于熟悉图数据库的同学可以快速上手
* 注：扫描过程不会上传任何形式的代码数据到服务端，请放心使用

### 三、工具的安装使用

* 下载安装：访问“铲子”官方网站，根据您的操作系统选择合适的安装包进行下载并安装。
* 配置环境：内置 java 运行环境，一键安装，无需配置。
* 开始扫描：启动程序后，点击新建任务即可。
* 查看结果：在漏洞窗口查看即可，可按需进行漏洞排序、筛选、标记等。
* 查看报告：在**任务**栏右键导出报告即可。

### 四、需求、bug、讨论

* 需求/bug：请在该仓库的 [issues](https://github.com/Chanzi-keji/chanzi/issues) 板块提交。
* 技术交流：请在该仓库的 [dissussions](https://github.com/Chanzi-keji/chanzi/discussions) 板块参与或发起讨论。
* 产品文档：GitHub上提供了详细的文档，可在 [wiki](https://github.com/Chanzi-keji/chanzi/wiki) 板块阅读。
* 官方网站：[www.chanzikeji.com](https://www.chanzikeji.com)
* 下载地址：[github下载](https://github.com/Chanzi-keji/chanzi/releases)
* 备用地址：[云盘下载](https://share.weiyun.com/7n4mAIlW)
