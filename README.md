# ML_Lab_one
Machine Learning Experiment One
线性回归和梯度下降

1. 读取实验数据，使用sklearn库的load_svmlight_file函数读取数据。
2. 将数据集切分为训练集和验证集，本次实验不切分测试集。使用train_test_split函数切分数据集。
3. 线性模型参数初始化，可以考虑全零初始化，随机初始化或者正态分布初始化。
4. 选择Loss函数及对其求导，过程详见课件ppt。
5. 求得所有样本对Loss函数的梯度G。
6. 取梯度G的负方向，记为D。
7. 更新模型参数W，W = W + eta*D。eta为学习率，是人为调整的超参数。
8. 在训练集上测试并得到Loss函数值L_train，在验证集上测试并得到Loss函数值L_validation。
9. 重复步骤5-8若干次，画出L_train和L_validation随迭代次数的变化图。


线性分类和梯度下降

1. 读取实验数据，使用sklearn库的load_svmlight_file函数读取数据。
2. 将数据集切分为训练集和验证集，本次实验不切分测试集。使用train_test_split函数切分数据集。
3. 支持向量机模型参数初始化，可以考虑全零初始化，随机初始化或者正态分布初始化。
4. 选择Loss函数及对其求导，过程详见课件ppt。
5. 求得所有样本对Loss函数的梯度G。
6. 取梯度G的负方向，记为D。
7. 更新模型参数W，W=W + eta*D。eta为学习率，是人为调整的超参数。
8. 选择合适的阈值，将计算结果大于阈值的标记为正类，反之为负类。在训练集上测试并得到Loss函数值L_train，在验证集上测试并得到Loss函数值L_validation。
9. 重复步骤5-8若干次，画出L_train和L_validation随迭代次数的变化图。
