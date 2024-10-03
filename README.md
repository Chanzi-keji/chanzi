# “铲子”SAST工具介绍

### 一、产品定位

* “铲子”是一款简单易用的JAVA SAST（静态应用程序安全测试）工具，旨在为安全工程师提供一款**简单、好用、价格厚道**的代码安全扫描产品。
* 官网：[www.chanzikeji.com](https://www.chanzikeji.com)

### 二、功能介绍

* 支持语言: java（Servlet、spring、dubbo、thirft、mybatis、jsp）
* 采用技术：污点分析，铲子会将java、xml（mybatis、dubbo）等统一构建数据流图，无需编译，然后进行污点分析。
* 支持漏洞：内置了 sql 注入、命令注入、文件上传、ssrf 等常见漏洞规则，用户可以自定义规则。
* 详细报告：生成详尽的漏洞报告，包括漏洞类型、危害等级、所在位置以及修复建议，帮助开发人员快速定位和解决问题。

### 三、工具的安装使用

* 下载安装：访问“铲子”官方网站，根据您的操作系统选择合适的安装包进行下载并安装。
* 配置环境：安装 java 即可运行，需要 jdk、jre 19及以上版本。
* 开始扫描：启动程序后，点击新建任务即可。
* 查看报告：在**任务**栏右键导出报告即可。

### 四、需求、bug、讨论

* 需求/bug：请在该仓库的 [issues](https://github.com/Chanzi-keji/chanzi/issues) 板块提交。
* 技术交流：请在该仓库的 [dissussions](https://github.com/Chanzi-keji/chanzi/discussions) 板块参与或发起讨论。
* 产品文档：GitHub上提供了详细的文档，可在 [wiki](https://github.com/Chanzi-keji/chanzi/wiki) 版本阅读。
