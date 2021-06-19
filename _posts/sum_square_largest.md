---
title: sum_square_largest
categories: java
---

函数名：sum_square_largest

功能：求解三个参数中较大的两个参数的平方和

思路：递归

### Java code

``` java
public sum_square_largest(double x, double y, double z){
    if (x<=y) && (x<=z){
        return Math.pow(y,2) + Math.pow(z,2);
    }else{
        return sum_square_largest(y, z, x);
    }
}
```
