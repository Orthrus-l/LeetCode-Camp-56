# LeetCode-Camp-56
代码随想录56期训练营打卡67天


第一天心得体会
耗费时长：2h30min    from20：00 to 22:30
今天复习了一下数组的内容，主要是二分查找和双指针法，对我来说还是二分查找需要多重复练习一下。
704 二分查找：找中最重要的是确定区间的两端，核心思路是使用mid去和target进行对比。
24  移除元素：如果不需要按照顺序的话，可以直接舍弃最末端的数字
977 有序数组的平方：需要额外的存储空间，直接比较两端的平方进行存储

第二天心得体会
耗费时长：2h         from21:00-23:00
今天主要是滑动窗口对我来说有点卡住，第二个螺旋矩阵对于边界值和循环的编写逻辑都没有答案那么流畅。暂时只完成两题，明天补上后面两题的内容。
209 最小子数组的长度：本题着重于找满足大于target的最短子串；第一步在left=0的条件下找到满足条件的子串；第二步收缩left，拓展right；
39 螺旋矩阵II：这道题最好选择左闭右开，然后一圈循环嵌套四个方向，利用startX和startY，ij来记录起始点和边界点。最终单独处理中心点。

