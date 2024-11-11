# Introduction to the "chanzi" SAST Tool

### I. Product Positioning
* The "chanzi" is a simple and easy-to-use JAVA SAST (Static Application Security Testing) tool, aiming to provide security engineers with a code security scanning product that is **simple, user-friendly, and reasonably priced**.
* Official Website: [www.chanzikeji.com](https://www.chanzikeji.com)

### II. Feature Introduction
* Supported Languages: java (Servlet&filter, spring, jfinal, netty, dubbo, thirft, mybatis, dropwizard, JDK built-in httpserver, jsp, xml, yaml, properties, etc.)
* Employed Technology: Taint analysis. The "Shovel" will uniformly construct data flow diagrams for java, xml (mybatis, dubbo), etc. without the need for compilation, and then conduct taint analysis. The vulnerability results can be conveniently read in the data flow window.
* Supported Vulnerabilities: It has built-in common CWE vulnerability rules such as SQL injection, command injection, file upload, SSRF, as well as component vulnerability rules for log4j, shiro, xstream, actuator, etc.
* Exporting Reports: Users can mark the vulnerabilities and export simple vulnerability reports, including the type of vulnerability, hazard level, location, and repair suggestions, helping developers quickly locate and solve problems.
* Decompilation: It supports decompilation scanning. You can select the jar or class files that need to be decompiled when creating a new task, or you can decompile and read the code of a single class or jar file during the auditing process.
* Editor: A multi-functional code editor. To make it more convenient to read the code and reduce the frequent switching between the SAST tool and the IDE by users, the editor has built-in jump and usage search functions for types, variables, and methods, enables quick search of the entire repository, and provides the code outline of files.
* Custom Rules: The custom rules adopt the Cypher query language, with a low learning threshold for users. Students who are familiar with graph databases can quickly get started.
* Note: The scanning process will not upload any form of code data to the server. Please use it with confidence.

### III. Installation and Use of the Tool
* Download and Installation: Visit the official website of the "Shovel", and select the appropriate installation package according to your operating system for downloading and installation.
* Environment Configuration: It has a built-in Java running environment and can be installed with one click without the need for configuration.
* Starting the Scan: After starting the program, click "New Task".
* Viewing the Results: You can view them in the vulnerability window, and sort, filter, mark, etc. the vulnerabilities as needed.
* Viewing the Reports: Right-click in the **Task** bar to export the report.

### IV. Requirements, Bugs, and Discussions
* Requirements/Bugs: Please submit them in the [issues](https://github.com/Chanzi-keji/chanzi/issues) section of this repository.
* Technical Exchanges: Please participate in or initiate discussions in the [dissussions](https://github.com/Chanzi-keji/chanzi/discussions) section of this repository.
* Product Documentation: Detailed documentation is provided on GitHub and can be read in the [wiki](https://github.com/Chanzi-keji/chanzi/wiki) section.
* Official Website: [www.chanzikeji.com](https://www.chanzikeji.com)
* Download Address: [GitHub Download](https://github.com/Chanzi-keji/chanzi/releases)
* Alternative Address: [Cloud Disk Download](https://share.weiyun.com/7n4mAIlW)
