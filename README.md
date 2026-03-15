# SZT-BigData-Analysis
# 🚉 深圳市公共交通百万级客流挖掘与 AI 预测系统

> **作者：** 徐天奇  | **专业：** 大数据管理与应用 (CUMTB)
> **核心技术：** PySpark, SQLite, Pandas, PyTorch, BI 可视化

---

## 🚀 项目概述
本项目基于深圳市 130 万条真实的公交/地铁刷卡数据，完整复现了从原始 JSON 数据清洗到深度学习预测的端到端（End-to-End）分析链路。

## 🛠️ 技术栈
* **大数据处理：** PySpark (分布式解析高维嵌套 JSON)
* **数据存储：** SQLite (构建本地轻量级事实表与维表)
* **数据分析：** SQL 窗口函数 (LEAD/LAG 计算通勤时长)
* **深度学习：** PyTorch (MLP 神经网络进行短时客流预测)
* **可视化：** Seaborn & Matplotlib (商业级看板设计)

## 📊 核心洞察 (Data Insights)

### 1. 城市交通潮汐分析
通过对全量数据的聚合统计，完美还原了深圳早晚高峰的“双峰效应”。
![24小时交通流量图](images/traffic_peak.png) 

### 2. 站点流量 Top 10
利用 SQL 统计出全网客流量最大的枢纽站（如五和、布吉、深圳北等），并对比了各站点的营收能力。
![Top10站点图](images/top10_stations.png)

### 3. AI 预测表现
采用 PyTorch 搭建的 MLP 模型在早高峰流量突变时期表现稳健，成功拟合了非线性趋势。
![PyTorch预测图](images/pytorch_prediction.png)

## 📜 个人认证与专业素养
* **华为云认证：** 持有 **HCDA-GaussDB 开发者认证**，具备底层数据库调优与分布式数仓架构思维。
* **工程化能力：** 熟练掌握 ELT 开发流程，具备百万级样本量下的数据清洗与特征工程实战经验。

---
