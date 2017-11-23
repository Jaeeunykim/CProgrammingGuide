# 숫자 출력

## %d, %i, %x, %o, %f

10진수 출력하기
```sh
#include <stdio.h>

int main()
{
	printf("%d 더하기 %d는 %d입니다.\n", 15,10,25);
	printf("%d 더하기 %d는 %d입니다.\n", 10,20,10+20);

	return 0;
}
```

10진수의 수를 8진수,16진수로 출력하기 
```sh
#include <stdio.h>

int main()
{
	printf("10진수 %d는 8진수로는 %o이고, 16진수로는 %x입니다\n", 16,16,16);
	//마이너스의 수 출력해보기 

	return 0;
}
```
실수 출력하기
```sh
#include <stdio.h>

int main()
{
	printf("10진수 정수 : %d\n", 0.5);
	printf("10진수 실수 : %f\n", 0.5);
	printf("10진수 실수 : %lf\n", 0.5);

	printf("소수점 이하 6이상 반올림 : %f\n", 0.1235678);

	return 0;
}
```


