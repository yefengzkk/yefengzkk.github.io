---
title: C++ 关键字解析（1）
layout: post

---
###导言
从自己大一开始上C++的课程到现在，已经有5年的历史了，当然中间也学了其它语言，我能说我对C++很熟悉吗？这恐怕要打一个问号。说说看过的关于C++的书吧。

    1.C++ Primer 看完一遍，除最后一章，其余都看完。
    2.Effective C++看过一遍。
    2.深入探索C++对象模型，前两章看完。  
    3.C++大学教程（本科课程用书）基本没看过  
再来说一说用C++完成的项目，除了零星写过的小程序使用的是C++，好像就没用过C++了。这里零星的小程序指的是数据结构课的小作业。所以至此为止，我得出的结论是我对C++不熟。为了更加深入的理解C++这门语言，我决定记录我理解的C++。于是就有了此篇。
###关键字
C++的关键字是指该语言的保留字，关键字不能用作程序的标识符。每个关键字都有特殊的含义。以下是C++所保留的关键字。

\* | \* | \*  |\*|\* 
-------|--------|-----------|------------|--------
*alignas*|*alignof*| asm   | auto   | bool 
break|case|catch|char|*char16_t*
*char32_t*|class|const|*constexpr*|const\_cast
continue|*decltype*|default|delete|do
double|dynamic\_cast|else|enum|explicit
export|extern|false|float|for
friend|goto|if|inline|int
long|mutable|namespace|new|*noexcept*
*nullptr*|operator|private|protected|public
register|reinterpret\_cast|return|short|signed
sizeof|static|*static\_assert*|static\_cast|struct
switch|template|this|*thread\_local*|throw
true|try|typedef|typeid|typename
union|unsigned|using|virtual|void
volatile|wchar\_t|while| | 

其中斜体标出的是C++ Primer第五版新加入的关键字，其余为和第四版相同的关键字，总数为73个。

###算术类型
在C++关键字中有一类是专门描述算术类型的，它们是`bool,char,char16_t,char32_t,double,float,int,long,short,wchar_t`。我们可以把`signed,unsigned`这两个表示有符号的关键字放在一起讨论。

    bool 只能取true，false，占一位。  
    char 占一个字节，八位。  
    double 双精度浮点数，在32位机器上占八个字节。  
    float 浮点数，  
    int 整数，在32位机器上占4个字节。  
    long 长整形  
    short   
    wchar_t 宽字符  
