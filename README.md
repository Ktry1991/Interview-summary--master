# eigentech.ai.test-master
<h1> 何荧的艾耕科技笔试题解答
<h2> 问题1：对于一个由小写字母组成的字符串，比如 "adcbf"，我们有一个小写字母到大写字母的可替换字典 {'a': ['B', 'C'], 'b': ['X']}，表示 'a' 可以替换为 'B' 或 'C'，'b' 可以替换为 'X'。请写一个程序打印出所有替换生成的字符串，在这个例子中，
<h2> 结果为：
<h2> BdcXf
<h2> CdcXf
<h2> 解题思路利用二叉树保存a的替换可能分支，在实际编程中使用2进制的0,1记录需要替换的C,B，从而代替二叉树保存分支，完成题目
<h2> 问题2：用随机梯度下降实现一个两层的神经网络，并生成数据测试模型训练过程。
<h2> 主要基于<a href='http://www.wildml.com/2015/09/implementing-a-neural-network-from-scratch/'>Implementing a Neural Network from Scratch in Python – An Introduction</a>的代码，改进为题目要求随机梯度完成模型构建
<h2> 附加题1：平时有阅读过数学之美，统计学习方法、Python机器学习——预测分析核心算法、利用Python进行数据分析
<h2> 附加题2：平时遇到问题多数是直接百度可以解决、偶尔会在csdn、Stack Overflow上提问。
