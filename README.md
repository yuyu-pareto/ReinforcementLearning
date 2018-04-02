# Reinforcement-Learning
强化学习练习
## 0 强化学习基础
整理了常见的基础方法
## 1 青蛙跳荷叶例子
利用价值迭代求出最优路径
## 2 导弹攻防对抗
模拟双方基地，按照gym格式编写环境，利用查表法和DQN方法分别来解决问题
## 3 强化学习入门书籍例程
学习了前八章程序
## 4 地铁线路
* 根据给的地铁线路找出最优（时间最短）路线
* Q学习分支较好的解决了问题
## 5 太阳帆轨迹转移优化-火星
* 搭建模型，太阳帆运动模型
* 调试技巧
    *   reward定义
    *   保持探索
    *   增加学习轮数
    *   增加网络大小
    *   总reward跨0
## 6 旅行商问题
* 利用深度强化学习解决简单旅行商问题
* DQN和A3C算法效果都一般般
## 8 太阳帆轨迹转移优化-使用极大值原理
* 使用极大值原理将原问题转化为一个寻优问题
* 使用A3C算法进行调试
* 效果很好，但是意义值得商榷
* 增加随机初始值到达终点
* 多起点效果不够好
    * 状态量的选择-太多容易学的较为麻烦
    * 尽量不用==，太绝对，条件不容易满足