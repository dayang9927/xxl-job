<p align="center" >
    <img src="https://www.xuxueli.com/doc/static/xxl-job/images/xxl-logo.jpg" width="150">
    <h3 align="center">全面解析XXL-JOB 2.3.1-SNAPSHOT</h3>
    <p align="center">
        此项目是 [xuxueli/xxl-job] 的分支，旨在全面解析XXL-JOB,提供全面的源码解析，并为源码添加详细的中文注释。
        <br>
        <a href="https://www.xuxueli.com/xxl-job/"><strong>-- 原项目Home Page --</strong></a>
        <br>
        <br>
        <a href="https://github.com/xuxueli/xxl-job/actions">
            <img src="https://github.com/xuxueli/xxl-job/workflows/Java%20CI/badge.svg" >
        </a>
        <a href="https://maven-badges.herokuapp.com/maven-central/com.xuxueli/xxl-job/">
            <img src="https://maven-badges.herokuapp.com/maven-central/com.xuxueli/xxl-job/badge.svg" >
        </a>
        <a href="https://github.com/xuxueli/xxl-job/releases">
         <img src="https://img.shields.io/github/release/xuxueli/xxl-job.svg" >
        </a>
        <a href="https://github.com/xuxueli/xxl-job/">
            <img src="https://img.shields.io/github/stars/xuxueli/xxl-job" >
        </a>
        <a href="https://hub.docker.com/r/xuxueli/xxl-job-admin/">
            <img src="https://img.shields.io/docker/pulls/xuxueli/xxl-job-admin" >
        </a>
        <a href="http://www.gnu.org/licenses/gpl-3.0.html">
         <img src="https://img.shields.io/badge/license-GPLv3-blue.svg" >
        </a>
        <a href="https://www.xuxueli.com/page/donate.html">
           <img src="https://img.shields.io/badge/%24-donate-ff69b4.svg?style=flat" >
        </a>
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

