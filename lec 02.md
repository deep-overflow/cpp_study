2 연산자는 무엇일까요?
================
더하기
```cpp
#include <iostream>

int main()
{
    int a = 1;
    int b = 3;

    int c = a + b;

    std::cout << c << std::endl;
}
```
빼기
```cpp
#include <iostream>

int main()
{
    int a = 12;
    int b = 7;

    int c = a - b;

    std::cout << c << std::endl;
}
```
곱하기
```cpp
#include <iostream>

int main()
{
    int a = 3;
    int b = 4;

    int c = a * b;

    std::cout << c << std::endl;
}
```
나누기(몫)
```cpp
#include <iostream>

int main()
{
    int a = 34;
    int b = 8;

    int c = a / b;

    std::cout << c << std::endl;
}
```
나누기(나머지)
```cpp
#include <iostream>

int main()
{
    int a = 34;
    int b = 8;

    int c = a % b;

    std::cout << c << std::endl;
}
```