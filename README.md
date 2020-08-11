# conflict

## 问题背景

天才少年爱迪生顺利地进入了华大学，开学时，他迎来了紧张而刺激的选课阶段，
由于华大学人均单身十年的手速，爱迪生感觉到强烈的抢课压力，由于爱迪生是现充，
手速不过关，他就想，如果自己能够快速过滤无效课程，是不是就可以弥补这个缺陷了，
于是他找到了你。

## 问题描述

你需要修改目录下的conflict.py，实现如下功能：

1. 读入两个数字n和m，分别表示已选课数目以及候选课数目
2. 在接下来的n+m行中，课程会被逐行读入，格式参见样例。
3. 对于每个课程，其开课时间与持续周数可能不同，你需要找到候选课中与已经选课冲突
的课，并将候选课名与冲突课名输出，格式参见样例

需要注意的是，如果有多个课与一节候选课冲突，其输出顺序按照课程号排序。
