关于链表得分析
****************
对于链表而言，增删改查四个操作的时间复杂度都为O(n),
但是，相对数组而言，链表是真正意义上的动态数据结构，
即不需要扩容这个操作，且在占内存方面，由于数组长度
的增加或者减少，可能会带来频繁的扩容操作，会使得内
存存在浪费得情况，另外，如果只是在链表得头部增加删
除元素，在尾部删除元素，性能上与数组没有差别，在内
存上得优势就会更加明显
****************

关于递归得分析
****************
递归四法则：
1.有基准情形
2.问题能够不断推进
3.所有递归都能运行
4.合成效益：递归的任意调用不要出现重复工作

能否使用就是用这个来进行判断
****************