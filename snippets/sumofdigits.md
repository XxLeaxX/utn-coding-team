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