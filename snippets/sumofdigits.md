# Sum of Digits

```c
int sumOfDigits(int n){
    //Calculate the sum of digits of n
    int sum = 0, count = 0;
    while(n != 0){
        sum += n % 10; // n % 10 is the unit of the number
        n /= 10; // n / 10 pops the unit of the number
        }
    return sum;
}
```

# Working in Action
[![Python Tutor](http://www.uadnan.com/wp-content/uploads/2014/10/PythonTutor-Logo-310x150.png)](https://goo.gl/Y0wg2N)
