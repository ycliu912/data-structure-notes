# 字符串的基本概念

## 字符串的定义

字符串的由零个或多个的字符组成的有限序列，一般表示为"a1a2...an"。

## 字符串的特征

- 串中字符的个数称为串的长度
- 任意连续的字符组成的子序列称为该串的子串
- 子串的位置为子串第一个字符在原串中的位置

## 字符串的基本运算

- 串的赋值
- 串的复制
- 求串的长度
- 判断两个串是否相等
- 串的拼接
- 求子串
- 查找子串的位置
- 插入子串
- 删除子串
- 替换子串
- 输出串


## 字符串的存储结构

### 顺序存储结构

```c
#define MaxSize 100  /*最多字符个数*/

typedef struct
{	
	char ch[MaxSize];	/*存放串字符*/
   	int len;			/*存放串的实际长度*/
} SqString;				/*顺序串类型*/
```

### 链式存储结构

```c
typedef struct node
{	
	char data;			/*存放字符*/
	struct node *next;	/*指针域*/
} LinkString;
```
