<div align="center">

<!-- 动态打字效果 -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=6C63FF&center=true&vCenter=true&random=false&width=700&lines=Hi+%F0%9F%91%8B%2C+I'm+JIA+XIANGYU;PhD+Student+%40+Beijing+Forestry+University;LLM+%7C+Remote+Sensing+%7C+Big+Data;Welcome+to+my+GitHub+Profile!)](https://git.io/typing-svg)

<!-- 社交媒体徽章 -->
[![GitHub followers](https://img.shields.io/github/followers/jxy0413?style=for-the-badge&logo=github&labelColor=1a1a2e&color=6C63FF)](https://github.com/jxy0413)
[![Meituan Email](https://img.shields.io/badge/Meituan-jiaxiangyu@meituan.com-FF6103?style=for-the-badge&logo=mail.ru&logoColor=white&labelColor=1a1a2e)](mailto:jiaxiangyu@meituan.com)
[![BJFU Email](https://img.shields.io/badge/BJFU-jia__xiangyu@bjfu.edu.cn-228B22?style=for-the-badge&logo=mail.ru&logoColor=white&labelColor=1a1a2e)](mailto:jia_xiangyu@bjfu.edu.cn)

<!-- 访客计数器 -->
<img src="https://komarev.com/ghpvc/?username=jxy0413&style=for-the-badge&color=6C63FF&labelColor=1a1a2e" alt="Profile Views"/>

</div>

---

## 🧑‍💻 About Me

<img align="right" alt="Coding" width="320" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif">

### 🎓 Education
- 🎓 **PhD Student** @ Beijing Forestry University (2025 - 2029)
- 🎓 **Master's Degree** @ Beijing Forestry University (2019 - 2022)
- 🎓 **Bachelor's Degree** @ Beijing Forestry University (2015 - 2019)

### 💼 Work Experience
- 🏢 **Meituan 美团** (2025 - Present)
- 🏢 **Ant Group 蚂蚁集团** (2024 - 2025)
- 🏢 **Meituan 美团** (2022 - 2024)

### 🔭 Current Focus
- 🤖 **Large Language Models (LLM)** - 大模型研究与应用
- 🛰️ **Remote Sensing Change Detection** - 遥感变化检测
- 📊 **Big Data Analytics** - 大数据分析与处理

---

## 📚 Publications

<table>
<tr>
<td width="80" align="center">
<img src="https://img.shields.io/badge/IEEE-00629B?style=flat-square&logo=ieee&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/SCI-Q1-red?style=flat-square" />
<br/>
<sub><b>2026</b></sub>
</td>
<td>

**Change-LISA: Language-Guided Reasoning for Remote Sensing Change Detection**

<p align="center">
  <img src="image/change_lisa.png" width="100%" />
</p>

<sub>
📖 <b>IEEE Transactions on Geoscience and Remote Sensing (TGRS)</b>, 2026, Early Access
<br/>
👥 <b>Xiangyu Jia (贾相宇)</b>, Zhibo Chen, Shengyi Zhang, Xiaojing Xue
<br/>
🏛️ Beijing Forestry University
<br/>
🔗 DOI: <a href="https://doi.org/10.1109/TGRS.2026.3684817">10.1109/TGRS.2026.3684817</a> | 
📄 <a href="https://ieeexplore.ieee.org/document/11482624">IEEE Xplore</a> | 
💻 <a href="https://github.com/jxy0413/changeLisa">Code</a>
</sub>

<details>
<summary>📝 摘要 | Abstract</summary>
<br/>
Remote sensing change detection (RSCD) is widely used for monitoring land-surface dynamics. Most models, however, output an unconditional "all-changes" map and do not account for user intents expressed in natural language. This can lead to spurious masks under counterfactual (i.e., negative/mismatched) queries. This paper studies language-guided reasoning change detection. Given a bitemporal image pair and a text instruction, the model outputs an instruction-conditioned change mask; the correct output can be an empty mask when the queried change is absent. To support this setting, ReasonRS-110K is built as a benchmark of <b>112,317</b> image–instruction–mask triplets. Instructions are organized into hierarchical reasoning levels (L1–L3) together with L0 negative queries for compliance evaluation. Change-LISA is proposed as a parameter-efficient framework that combines a frozen Siamese SAM encoder and an explicit difference/fusion module with a multimodal LLM (LLaVA). The LLM emits a token whose embedding prompts a lightweight mask decoder. Only LoRA adapters and the decoder are optimized. On ReasonRS-110K, Change-LISA reaches <b>63.1 IoU</b> and <b>77.3 F1</b> on positive-query levels (L1–L3) and <b>95.4 NCA</b> with <b>0.12 FPA</b> on L0 negative queries, outperforming representative CD-only, RIS, and MLLM baselines.
</details>

![Remote Sensing](https://img.shields.io/badge/Remote_Sensing-228B22?style=flat-square)
![Change Detection](https://img.shields.io/badge/Change_Detection-FF6B6B?style=flat-square)
![Language-Guided](https://img.shields.io/badge/Language--Guided-6C63FF?style=flat-square)
![Multimodal LLM](https://img.shields.io/badge/Multimodal_LLM-FF6103?style=flat-square)

</td>
</tr>
<tr>
<td width="80" align="center">
<img src="https://img.shields.io/badge/IEEE-00629B?style=flat-square&logo=ieee&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/SCI-Q2-orange?style=flat-square" />
<br/>
<sub><b>2026</b></sub>
</td>
<td>

**CSGANet: Lightweight Channel-Split Group Attention for High-Resolution Remote Sensing Change Detection**

<p align="center">
  <img src="image/csganet.png" width="100%" />
</p>

<sub>
📖 <b>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (JSTARS)</b>, 2026, pp. 1-15
<br/>
👥 <b>Xiangyu Jia (贾相宇)</b>, Zhibo Chen, Shengyi Zhang
<br/>
🏛️ Beijing Forestry University
<br/>
🔗 DOI: <a href="https://doi.org/10.1109/JSTARS.2026.3659056">10.1109/JSTARS.2026.3659056</a> | 
📄 <a href="https://ieeexplore.ieee.org/document/11367786">IEEE Xplore</a> | 
💻 <a href="https://github.com/jxy0413/csganet">Code</a>
</sub>

<details>
<summary>📝 摘要 | Abstract</summary>
<br/>
Change detection (CD) in remote sensing imagery is a fundamental tool for Earth monitoring. We propose CSGANet, a lightweight Siamese framework featuring two key innovations: a channel-split group attention module (CSGA) to selectively integrate complementary local, directional, and global contexts, and an Adaptive PathMixing Module (AdmPM) for globally guided, boundary-preserving downsampling. Extensive experiments on LEVIR, SYSU, and S2Looking benchmarks demonstrate that CSGANet achieves competitive accuracy with a compact footprint, reaching F1 scores of <b>91.82%</b>, <b>84.26%</b>, and <b>66.11%</b>, respectively, with only <b>4.15M</b> parameters and <b>16.39 GFLOPs</b>.
</details>

![Remote Sensing](https://img.shields.io/badge/Remote_Sensing-228B22?style=flat-square)
![Change Detection](https://img.shields.io/badge/Change_Detection-FF6B6B?style=flat-square)
![Lightweight Networks](https://img.shields.io/badge/Lightweight_Networks-6C63FF?style=flat-square)
![Group Attention](https://img.shields.io/badge/Group_Attention-FF6103?style=flat-square)

</td>
</tr>
<tr>
<td width="80" align="center">
<img src="https://img.shields.io/badge/EI-Indexed-blue?style=flat-square" />
<br/>
<sub><b>2021</b></sub>
</td>
<td>

**森林生态站大数据快速存储与索引方法**

Fast Storage and Indexing Method of Big Data in Forest Ecological Station

<sub>
📖 农业机械学报 (Transactions of the Chinese Society for Agricultural Machinery), 2021, 52(8): 195-204
<br/>
👥 王新阳, <b>贾相宇</b>, 陈志治, 崔晓晖, 许福
<br/>
🏛️ 北京林业大学信息学院 | 国家林业和草原局林业智能信息处理工程技术研究中心
<br/>
🔗 DOI: <a href="https://doi.org/10.6041/j.issn.1000-1298.2021.08.019">10.6041/j.issn.1000-1298.2021.08.019</a>
</sub>

<details>
<summary>📝 摘要 | Abstract</summary>
<br/>
针对森林生态站中大量图像、视频、GIS数据等非结构化数据以及生态指标等结构化数据存储效率低、检索性能差的问题，提出了基于Hadoop和HBase的森林生态站大数据存储框架。设计预分区算法保证数据在集群中均匀分布，科学设计RowKey实现生态数据的快速检索，基于ElasticSearch的二级非主键索引技术优化多条件检索。实验结果表明，系统检索速度提升3.99倍，每秒查询数提升1.88倍，系统响应时间降低69.5%。
</details>

![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=flat-square&logo=apachehadoop&logoColor=black)
![HBase](https://img.shields.io/badge/HBase-E25A1C?style=flat-square&logo=apache&logoColor=white)
![ElasticSearch](https://img.shields.io/badge/ElasticSearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Big Data](https://img.shields.io/badge/Big_Data-FF6B6B?style=flat-square)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

### 💻 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=for-the-badge&logo=scala&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### 🤖 AI & Machine Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### 📊 Big Data
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black)
![Flink](https://img.shields.io/badge/Apache_Flink-E6526F?style=for-the-badge&logo=apacheflink&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Hive](https://img.shields.io/badge/Apache_Hive-FDEE21?style=for-the-badge&logo=apachehive&logoColor=black)

### 🛰️ Remote Sensing & GIS
![GDAL](https://img.shields.io/badge/GDAL-5CAE58?style=for-the-badge&logo=gdal&logoColor=white)
![QGIS](https://img.shields.io/badge/QGIS-589632?style=for-the-badge&logo=qgis&logoColor=white)
![Google Earth Engine](https://img.shields.io/badge/Google_Earth_Engine-4285F4?style=for-the-badge&logo=google-earth&logoColor=white)

### ⚙️ Backend & Database
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)

### 🔧 Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">
  
<img width="49%" src="https://github-readme-stats.vercel.app/api?username=jxy0413&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1a1a2e&title_color=6C63FF&icon_color=6C63FF&text_color=ffffff" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=jxy0413&theme=tokyonight&hide_border=true&background=1a1a2e&ring=6C63FF&fire=FF6B6B&currStreakLabel=6C63FF" />

<img width="60%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jxy0413&layout=compact&theme=tokyonight&hide_border=true&bg_color=1a1a2e&title_color=6C63FF&text_color=ffffff&langs_count=8" />

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=jxy0413&theme=tokyo-night&hide_border=true&bg_color=1a1a2e&color=6C63FF&line=6C63FF&point=FF6B6B)](https://github.com/jxy0413)

</div>

---

## 🤝 Let's Connect

<div align="center">

<a href="https://github.com/jxy0413"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="mailto:jiaxiangyu@meituan.com"><img src="https://img.shields.io/badge/Meituan_Mail-FF6103?style=for-the-badge&logo=mail.ru&logoColor=white" /></a>
<a href="mailto:jia_xiangyu@bjfu.edu.cn"><img src="https://img.shields.io/badge/BJFU_Mail-228B22?style=for-the-badge&logo=mail.ru&logoColor=white" /></a>

</div>

---

<div align="center">

### 🌟 From Industry to Academia, Pursuing the Dream of Technology

**美团 → 蚂蚁集团 → 美团 → PhD @ 北京林业大学**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
