# 간단한 입출력 
C언어 문법 공부를 들어가기에 앞서 간단한 입출력을 해볼수 있습니다.

## Hello World!

```sh
#include <stdio.h>

int main()
{
	printf("Hello, World!\n");

	reutrn 0;
}
````

```sh
#include <stdio.h>

int main()
{
	printf("Hello,");
	printf("World!");
	printf("\n");

	reutrn 0;
}
```
## scanf함수 이용

```sh
#include <stdio.h>

int main()
{
	char name[10];
	printf("What is your English name?\n");
	scanf("%s", &name);
	printf("%s!, Nice meet you, I'm so happy to meet you\n", name);

	return 0;
}
```

## 출력 서식 문자
 서식문자 | 출력 형태					 
--- | ---|
 %d, %i   | 10진수 정수(양수음수) 		 
 %x, %o   | 16진수, 8진수 정수(양수만)  
 %f, %lf  | 10진수 실수(양수음수)		 
 %c	   | 한 개의 문자 				 
 %s	   | 문자열						 
 %u 	   | 10진수 정수(양수)			 
 %e        | e 표기법에 의한 실수 
 %E 	   | E 표기법에 의한 실수 
 %%	   | % 기호출력					 

## 주요 진법 수의 표현 

 10진법	| 8진법	| 16진법
 --- | ---| ---|
 0	|	0	|	0
 1	|	1	|	1
 2	|	2	|	2
 3	|	3	|	3
 4|4|4
 5|5|5
 6|6|6
 7|7|7
 8|10|8
 9|11|9
 10|12|A
 11|13|B
 12|14|C
 13|15|D
 14|16|E
 15|17|F
