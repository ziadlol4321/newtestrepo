<h1><b>Fibbonacci Report</b></h1>

## Different ways to code fibbonacci sequence on your favourite compiler!
<ol>
<li>first </li>
<li>second </li>
<li>third </li>
</ol>

## THE RECURSIVE WAY

```// Fibonacci Series using Recursion
#include <bits/stdc++.h>
using namespace std;
 
int fib(int n)
{
    if (n <= 1)
        return n;
    return fib(n - 1) + fib(n - 2);
}
 
int main()
{
    int n = 9;
    cout << fib(n);
    getchar();
    return 0;
}```
