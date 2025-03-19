# 2235. Add Two Integers

![Problem Image](./problem-image.png)

## Problem Description
Given two integers `num1` and `num2`, return the sum of the two integers.

## Explanation
Bu soru bizden iki tam sayıyı toplama işlemi yapmamızı istiyor. Verilen iki tam sayıyı toplayarak sonucu döndürmemiz gerekiyor.

## Solution Analysis
Bu problem oldukça basit bir toplama işlemi gerektiriyor. İki tam sayıyı toplamak için toplama operatörünü (+) kullanabiliriz.

### Time Complexity
- O(1) - İşlem, iki tam sayının basit bir şekilde toplanmasını içerir ve sabit zaman alır.

### Space Complexity
- O(1) - Sonucu saklamak için yalnızca sabit miktarda ekstra alan kullanılır.

## Code
```java
class Solution {
    public int sum(int num1, int num2) {
        return num1 + num2;
    }
}
``` 