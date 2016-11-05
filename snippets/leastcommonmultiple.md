# Least Common Multiple
There are several versions for calculing the LCM

## Version 1: Using GCD
```c
unsigned lcm(unsigned a, unsigned b){
  if (a == 0 || b == 0){  
    return 0;
    }
  return a * (b / gcd(a,b));
  }
```
# Working in Action
[![Python Tutor](http://www.uadnan.com/wp-content/uploads/2014/10/PythonTutor-Logo-310x150.png)](https://goo.gl/F5UvMU)