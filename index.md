---
layout: home
title: 主页
nav_exclude: true
seo:
  type: 课程
  name: 线性代数
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->

## 关于本课程

TBD.

## 课程基本信息

**主讲人:** [杨启哲](https://basics.sjtu.edu.cn/~yangqizhe/), qzyang(at)shnu.edu.cn

**课程时间地点:** &ensp;&nbsp;8:00 a.m.- 9:30 a.m. &emsp; 每周三(1-16周), 奉贤3教楼401
 <br/>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&ensp;&nbsp;9:45 a.m.- 11:15 a.m. &emsp;每周五(1-16周), 奉贤3教楼401


 更多信息可以关注 [课程安排](schedule.md).



## 课程反馈

TBD.

<!--
我们建立了一个长期的课程反馈问卷:

- [《线性代数》课程调查问卷](https://www.wjx.cn/vm/QBVxm2f.aspx#)

欢迎大家提出关于本课程的问题或建议。
-->


## 之前的课程资料

- [2024年春季学期](https://www.la2024s.spacepenguin.com.cn)

## 课程通知

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

