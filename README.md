# Single-dataset:基于Seurat包的sc全流程分析
 You can also look at: https://satijalab.org/seurat/   
 五大R包，唯Seurat独尊  
 大家需要熟练掌握5个R包，分别是: scater,monocle,Seurat,scran,M3Drop  
## 基本步骤
 step1: 创建对象   
 step2: 质量控制QC   
 step3: 表达量的标准化和归一化  
 step4: 去除干扰因素(多个样本整合)  
 step5: 判断重要的基因  
 step6: 多种降维算法  
 step7: 可视化降维结果  
 step8: 多种聚类算法  
 step9: 聚类后找每个细胞亚群的标志基因  
 step10: 继续分类（case-study）  
## Seurat流程教学
降维：  
https://holab-hku.github.io/Fundamental-scRNA/  

聚类与细胞注释：  
https://github.com/pkuerten/single_cell_clustering_annotation.github.io/blob/main/index.md  

读入数据的后缀类型：  
（1）.h5文件(所以需要hf5r的R包)
e.g. https://github.com/holab-hku/Fundamental-scRNA/blob/master/data/10k_PBMC.h5  

## 其他小众流程：
