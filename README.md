# sort-binaryTree

这里先附上一个个人觉得总结的不错的 关于经典算法总结的博客 [戳我](https://juejin.im/post/57dcd394a22b9d00610c5ec8) <br>

自己尝试用js编写了几种:<br>
这里都是以从小到大排列<br>
# 1.冒泡排序 
原理：比较两个元素，如果前一个比后一个大，那么就交换位置。然后一对一对比较；

# 2.选择排序
原理：首先在未排序的序列中找到最小值，然后在剩余的未排列的序列中找到最小值，依次循环下去

# 3.插入排序
原理： 对于未排列的数据，从已排列的队列从后往前，找到合适的位置插入

#4. 快速排序
原理： 从数据的中间找一个元素做为基准，比他小的就排左边，比他大就放右边，然后再左右分区中继续找基准，依次循环下去


## 二叉树

# 排序二叉树  
左节点小于父节点的值 右节点大于父节点的值

# 有三种遍历方法
1.中序遍历<br>  先看有没有左边子树  有的话就遍历完左  然后返回父节点 最后再遍历右 可以从小到大遍历


2.前序遍历 <br>
可以用来复制一个二叉树<br>
先访问当前节点 再访问左 再右<br>


3.后序遍历<br>
先访问左子树  然后右子树 最后根节点


# 二叉树查找

找到最小值节点 只用从根节点一直访问左节点<br>
找最大节点 类似
