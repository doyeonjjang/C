# 5주차 C언어 실습
  - 5주차 실습1
  ```c
  #include <stdio.h>
  int main(void)
  {
  int number;
  printf("정수를 입력하시오:");
  scanf("%d", &number);
  if( number > 0 )
  printf("양수입니다.");
  printf("입력된 값은 %d입니다.", number);
  return 0;
  }
```

- 5주차 실습2
```c
#include <stdio.h>
int main(void)
{
int number;
printf("정수를 입력하시오:");
scanf("%d", &number);
if( number % 2 == 0 )
printf("입력된 정수는 짝수입니다.\n");
else
printf("입력된 정수는 홀수입니다.\n");
return 0;
}
```

- 5주차 실습3
```c
#include <stdio.h>
int main(void)
{
char ch;
printf("문자를 입력하시오: ");
ch = getchar();
if( ch >= 65 && ch <= 90 )
printf("%c는 대문자입니다.\n", ch);
else if( ch >= 97 && ch <= 122 )
printf("%c는 소문자입니다.\n", ch);
else if( ch >= 48 && ch <= 57 )
printf("%c는 숫자입니다.\n", ch);
else
printf("%c는 기타문자입니다.\n", ch);
return 0;
}
```
