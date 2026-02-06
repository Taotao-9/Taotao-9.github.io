---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

大家好，我是姚浩涛！目前就读于**[合肥工业大学](https://www.hfut.edu.cn/)**物流工程与管理研究生一年级。
我的研究兴趣与方向主要集中于**车辆与无人机协同路径规划**，研究在多仓库多无人机多车辆条件下的实时路径规划。

Hello everyone, I'm Haotao Yao! I'm currently a first-year graduate student in Logistics Engineering and Management at **[Hefei University of Technology](https://www.hfut.edu.cn/)**. My research interests and focus are mainly on **collaborative path planning between vehicles and drones**, specifically real-time path planning under conditions involving multiple warehouses, multiple drones, and multiple vehicles.


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 参加“第 X 届中国物流学术年会”，上海
- *2024.09*: &nbsp;🎉🎉 关于“多无人机协同路径规划”的最新综述论文已投稿至《xxxxx》期刊。
- *2023.09*: &nbsp;🎉🎉 已在 GitHub 上发布针对 VRP 问题的 Python 基础算法库。

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AEI 2026</div><img src='images/showcase.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-depot electric vehicle routing problem with drones considering time-dependent traffic]((https://linkinghub.elsevier.com/retrieve/pii/S1474034625009012))

**Hao Fan**, Kai Liu, Jiangbo Wang, Jian Zhao

[**Project**](https://www.elsevier.com/locate/aei) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- 探索在多仓库多卡车多无人机条件下，无人机与车辆的最优路径规划。实验证明，MD-EVRPD-TDT可以很好地解决此类问题，并相较于传统算法效率提高10%-40%。

[**数据集及实验源码**](https://github.com)
</div>
</div>

# 🎖 Honors and Awards
- *2025.09* 荣获硕士研究生学业x等奖学金，合肥工业大学
- *2024.09* 获全国大学生xxxx竞赛国家/省x等奖，合肥工业大学
- *2024.09* 获全国大学生xxxx竞赛国家/省x等奖，合肥工业大学
- *2024.07* 获评普通高等学校省级“优秀毕业生”，安徽省
- *2023.07* xxxx大学“三好学生”
- *2023.07* xxxx大学“优秀班干部”
# 📖 Educations
- *2025.06 -  now*, 合肥工业大学，物流工程与管理专业，车辆与无人机协同路径规划研究方向，师从[谢睿达](https://ruida-xie.github.io/)老师。
- *2020.09 - 2024.06*, 合肥大学，工商管理专业，平均绩点：x.xx。


# 💻 Internships
- *2024.06 – 2024.09*, 京东物流 (JD Logistics) | 算法实习生，中国北京
- 项目描述：参与“最后一公里”智能配送路径优化系统开发。
负责城市末端多点配送路径规划（VRP）的算法实现，利用 Python 调用 Gurobi 求解器进行模型求解。
针对车辆与无人机协同配送场景，设计并对比了贪婪算法与禁忌搜索算法的优化效率。
处理百万级配送订单数据，通过经纬度聚类分析优化了配送区域划分，使平均配送时长缩短了 12%。
