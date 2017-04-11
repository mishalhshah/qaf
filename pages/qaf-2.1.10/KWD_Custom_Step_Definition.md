---
title: KWD Custom Step Definition
sidebar: qaf_2_1_10-sidebar
permalink: qaf-2.1.10/KWD_Custom_Step_Definition.html
folder: qaf-2.1.9
tags: [kwd,scenario]
---

Steps can be defined in kwl

The Basic Step definition is following. 
 
```
STEP-DEF|<stepName>|{"description":"<meaningfull step description>",<meta-key>:<meta-value>}
<first stepName>|<step input parameters>|<step out parameters>
...
<nth stepName>|<step input parameters>|<step out parameters>
END||
```


While execution make sure required kwl files are mentioned in step.provider.pkg property as below

```properties
step.provider.pkg=com.test;scenarios
```