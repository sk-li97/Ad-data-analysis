# Ad-data-analysis

## Overview
This repository contains Python scripts for analyzing advertising performance data, focusing on conversion funnel metrics (CTR, CVR) across different products. The analysis aims to evaluate the effectiveness of advertising materials and optimize resource allocation.主要做复盘细节前大的概览的分析，包括数据的基本统计，数据的趋势图，筛选优质广告产品（高回报低成本），用户行为链路的漏斗分析，和不同产品之间的对比，目的是找到大的问题链路。



## Requirements
- Python 3.x
- Libraries:
  - `pandas`
  - `matplotlib`
- Install dependencies:
  ```bash
  pip install pandas matplotlib

## Data 

File: 产品报表_2025-04-18-2025-07-16_分日 (1).xlsx 所有具体数据已脱敏处理
Sheet: sheet1
Columns:
- 产品名称 (Product Name)
- 产品ID (Product ID)
- 时间 (Date)
- 花费 (Spend)
- 曝光量 (Impressions)
- 点击量 (Clicks)
- 下载量 (Downloads)
- 激活量 (Activations)
- 收益 (Revenue)
- ROAS (Return on Ad Spend)


Data includes 571 rows across products like 魔仙堡, 玲珑, 小蓝, etc.
