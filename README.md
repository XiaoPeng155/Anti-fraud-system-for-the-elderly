项目思路
1.	使用“jieba”分词库对待检测的文本进行分词
2.	构建训练集（由文本特征和相应的标签组成），并使用随机森林算法构建分类器
3.	训练模型，并将其保存到文件 “model.pkl” 中，方便后续重用
4.	加载先前保存的模型，测试新数据，并输出预测结果
