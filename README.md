#题目1：DOTA<br>
<br>
题目描述：<br>
很多童鞋喜欢玩一些lol、dota这类游戏，这类游戏有一个特点，在你不死的情况下连续杀人会有不同称号。
下面输入一组字符，其中只包含K和D，K代表杀敌，D代表死亡，求他最高称号。
0/1/2 - You are a Foolish Man
3 - You are on a Killing Spree 
4 - You are Dominating 
5 - You have a Mega-Kill 
6 - You are Unstoppable
7 - You are Wicked Sick
8 - You have a M-m-m-m....Monster Kill 
9 - You are Godlike 
10+ - You are Beyond Godlike (Somebody kill him!)<br>
<br>
输入描述：<br>
两个用空格隔开的正整数m n<br><br>
<br>
输出描述：<br>
m和n的最小公倍数和最大公约数，用空格隔开<br>
<br>
样例输入：<br>
6 15<br>
<br>
样例输出：<br>
30 3<br>
<br>
数据规模与约定：<br>
0\<m,n<br>
<br>
#题目2：格式整理<br>
<br>
问题描述：<br>
输入一串字符串（其中可能含有多个回车），并对其进行格式整理。格式整理的规则为：去除所有的回车符，将所有大写字符转为小写字符。<br>
<br>
输入描述：<br>
一段未经整理的字符串，其中可能含有多个回车，连续两个英文句号（.）表示输入结束（格式整理时，只保留一个句号）。<br>
<br>
输出描述：<br>
整理之后的字符串。<br>
<br>
样例输入：<br>
tHe anSWer to life,the Un<br>
iverse,ANd everythi<br>
ng is 42..<br>
<br>
样例输出：<br>
the answer to life,the universe,and everything is 42.<br>
<br>
提示：<br>
不要用scanf、gets、gets_s等函数来输入字符串，因为输入的内容包含多个回车，且不以回车为输入结束的标志。<br>
<br>
数据规模与约定：<br>
字符串长度不超过1024。<br>
<br>
#题目3：最长上升子序列<br>
<br>
题目描述：<br>
给出一个数组A，数组中有n个元素，找出其中的最长上升子序列，使A[m1]\<A[m2]\<...\<A[mk]，其中m1\<m2\<...\<mk。<br>
<br>
输入描述：<br>
第一行，一个整数n<br>
第二行，n个用空格隔开的整数<br>
<br>
输出描述：<br>
最长上升子序列的长度<br>
<br>
样例输入：<br>
5<br>
9 3 6 2 7<br>
<br>
样例输出：<br>
3<br>
<br>
数据规模与约定：<br>
n<=1024<br>
<br>
