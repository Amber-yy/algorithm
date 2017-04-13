#题目1：星系炸弹
=====
题目描述：<br>
在X星系的广袤空间中漂浮着许多X星人造“炸弹”，用来作为宇宙中的路标。<br>
每个炸弹都可以设定多少天之后爆炸。<br>
比如：阿尔法炸弹2015年1月1日放置，定时为15天，则它在2015年1月16日爆炸。<br>
有一个贝塔炸弹，2014年11月9日放置，定时为1000天，请你计算它爆炸的准确日期。<br>
<br>
请填求出该日期，格式为 yyyy-mm-dd  即4位年份2位月份2位日期。比如：2015-02-19<br>
<br>
提示：这是蓝桥杯比赛的原题，这种题目求解方式不限，但是最好通过编写程序来求解<br>
<br>

#题目2：数列处理<br>
=====

题目描述:<br>
输入一列整数，输出它们的总和、最大值、最小值、并从大到小输出。<br>
<br>
输入描述<br>
第1行：一个整数n，表示一共有n个整数<br>
第2行：n个整数<br>
<br>
输出描述：<br>
一行数字，第一个：总和；第二个：最大值；第三个：最小值。以后n个：降序排列的数字。<br>
<br>
样例输入：<br>
6<br>
2 5 5 4 9 4<br>
<br>
样例输出：<br>
29 9 2 9 5 4 2<br>
<br>
时间限制：1000ms<br>
空间限制：128MB<br>
<br>
数据规模与约定：<br>
n<=100000<br>
<br>
提示：<br>
和昨天最后一道题类似，就当复习快速排序。<br>
<br>

#题目3：图标缩放<br>
=====
现在假设你是个店员,为了方便/准确/最优的找零钱,你设计了一个程序.该程序应该实现如下功能:<br>
第一行输入客户所给你金额<br>
第二行输入客户消费的总金额<br>
第三行输出应找的总零钱是多少<br>
第四行输出各种面额的张数(总金额之和要与第三行的数相等,并且要求货币总张数是最少的方案输出)<br>
注:为了简单,假设上述中的金额都是整数,现规定金额的面值为100,50,20,10,5,1元。<br>
<br>
输入描述：<br>
第一行，一个整数m，表示客户所付的金额,如100<br>
第二行，一个整数n，表示商品的总计金额,如25<br>
<br>
输出描述：<br>
第一行，一个整数，表示应找的零钱。<br>
第二行，输出 金额面值1*张数1+金额面值2+张数2+....+金额面值N*张数N=总零钱数(面值较大的零钱优先排在前面，如５０元比２０元大，应排在前面)<br>
<br>
样例输入1：<br>
100<br>
25<br>
样例输出1：<br>
75<br>
50*1+20*1+5*1=75<br>
<br>
样例输入2：<br>
95<br>
2<br>
样例输出2：<br>
93<br>
50*1+20*2+1*3=93<br>
<br>
时间限制：1000ms<br>
空间限制：128MB<br>
<br>
数据规模与约定：<br>
m<n<10000<br>
<br>
提示：<br>
这道题用到的算法是贪心法，这算是相对简单的一种算法，有兴趣的同学可以了解一下。<br>
