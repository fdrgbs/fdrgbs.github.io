---
layout: post
title: MAVEN按环境加载不同的配置文件
date: 2019-02-27
category: 技术
tags: [maven]
keywords: maven,filters
---

## 按环境加载不同的配置文件
### JS不同环境的加载
 * java下的filters
 
![](/Users/sgl/Downloads/java-filters.png "过滤器样例")
 
 * maven下的profile
 
 ```
  <profile>
            <!--生产环境-->
            <id>production</id>
            <properties>
                <!--Environment-->
                <env>production</env>
 ```