<p align="center" >
    <h3 align="center">全面解析XXL-JOB 2.3.1-SNAPSHOT</h3>
    <p align="center">
        此项目是 [xuxueli/xxl-job] 的分支，旨在全面解析XXL-JOB,提供全面的源码解析，并为源码添加详细的中文注释。
        <br>
        <br>
        <br>
    </p>
</p>

### 写在前面

致敬，原理分析，架构图

### 分析方式

使用逆向分析方法

### SPRING-BOOT执行器包结构

```tex
├─java
│  └─com
│      └─xxl
│          └─job
│              └─executor
│                  ├─core.config.XxlJobConfig.java           #执行器配置类
│                  └─service.jobhandler.SampleXxlJob.java    #执行器任务开发示例
│                  └─XxlJobExecutorApplication               #执行器主启动类
└─resources
    └─application.properties                                 #application
```

