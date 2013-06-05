SISElective
===========

## SISElective 是什么

**SISElective** 项目旨在使用现今流行的技术建立一个老旧 MYSISE 选课系统的开源替代品。


## 第一部分：系统分析

### 一、模型

#### 课程

* 代号
* 名称
* 学分
* 学年学期
* 【班】列表

#### 课程:班

* 代号
* 【课】列表
* 是否小班

大小班约定：

* 纯字母代号 `AA` 代表大班
* 字母加数字 `AA01` 代表小班
* 当一个大班附带小班的时候，大班必须连同所附带（字母相同）的其中一个小班一起选

#### 课程:班:课

* 那些周
* 第几节
* 教师
* 地点

#### 学生

* 【课程:班】列表


### 二、瓶颈


### 三、优化方案
