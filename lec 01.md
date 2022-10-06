1 변수는 무엇일까?
==============
1, 2, 3과 같은 정수를 표현하기 위해서는 int형을 사용해야 한다.
```cpp
#include <iostream>

int main()
{
    int a = 3;
    int b = 6;

    int c = a + b;
    std::cout << c << std::endl;
}
```
1.2, 3.14, 2.794와 같은 소수점이 있는 숫자를 표현하기 위해서는 float형을 사용해야 한다.
```cpp
#include <iostream>

int main()
{
    float a = 1.2;
    float b = 2.3;

    float c = a + b;
    std::cout << c << std::endl;
}
```