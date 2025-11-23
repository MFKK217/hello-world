# ACM题解
此博客用于留存我在刷acm题库中遇见的不会的题目的题解，以及对应知识点的扩展
# 1.题目
题目描述
编写程序，从键盘输入一个字符，输出它的ASCII码值。
输入
测试数据有多组。每组输入一个字符。
输出
输出字符对应的十进制ASCII码值。
# 题解
#include <iostream>
using namespace std;
char a;
while(cin >> a ){          //输入多组数据，
cout << (int)a << endl;    //（int）a将字符转换为对应的ASCII编码值
}
return 0;
}
