# Greatest Common Divisor
There are 3 version for the GCD Euclidean Algorithm, **only version 2 and 3 are recommended for using.**

## Version 1: Substraction (Inefficient)
```c
unsigned gcd(unsigned a, unsigned b){
  while (a != b){
    if (a > b){
      a = a - b;
      }
    else{
      b = b - a;
      }
    }
  return a;
  }
```
# Working in Action
[![Python Tutor](http://www.uadnan.com/wp-content/uploads/2014/10/PythonTutor-Logo-310x150.png)](https://goo.gl/GV3jmH)

***

## Version 2: Division (Procedural)
```c
unsigned gcd(unsigned a, unsigned b){
  unsigned t;
  while (b != 0){
    t = b;
    b = a % b;
    a = t;
    }
  return a;
  }
```
# Working in Action
[![Python Tutor](http://www.uadnan.com/wp-content/uploads/2014/10/PythonTutor-Logo-310x150.png)](https://goo.gl/0EnGih)

***

## Version 3: Division (Recursive)
```c
int gcd(int a, int b){
  if (b == 0){
    return a;
    }
  return gcd(b, a % b);
  }
```
# Working in Action
[![Python Tutor](http://www.uadnan.com/wp-content/uploads/2014/10/PythonTutor-Logo-310x150.png)](https://goo.gl/XlMdRD)