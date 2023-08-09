# 中文文本摘要任务
## 模型：
- bart-base-chinese
- cpt-base

## 数据集：
Multilingual Amazon Reviews Corpus(zh) 中文，（test,validation）总计10000条数据

## 评测指标：
ROUGE 

## fine-tuning 后评测结果
模型|Rouge1|Rouge2|RougeL
--|--|--|--
bart-base-chinese| 0.464900| 0.053300| 0.470200	
cpt-base| 0.140000|	0.020000|	0.140000
