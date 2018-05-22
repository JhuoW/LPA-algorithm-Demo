# LPA-algorithm-Demo
a demo of a community detection algorithm


based on python3.6.x ,networkx2.x

LPA-algorithm的基本流程如下：
首先每个节点有一个自己特有的标签，节点会选择自己邻居中出现次数最多的标签，如果
每个标签出现次数一样多，那么就随机选择一个标签替换自己原始的标签，如此往复，直
到每个节点标签不再发生变化，那么持有相同标签的节点就归为一个社区。
