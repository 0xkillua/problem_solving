# The problem H. Last Digit and Last problem
[problem_sum](https://codeforces.com/group/P9uFhztGih/contest/401786/problem/H)
## Hints
single name A ,
 which A contains no more than 10 characters
 
## Solution python
```python
n1,n2 = (map(int, input().split()))
n1%=10
n2%=10
print(n1+n2)
```
## Solution java
```java
import java.util.Scanner;
 
public class Myproject {
 
    public static void main(String[] args) {
         
     Scanner input= new Scanner(System.in);
      
     
    long s = input.nextLong();
     long m = input.nextLong();
      s%=10;
      m%=10;
       System.out.println(s+m);
     
        
    }
}
```
## Solution c++
```c++
#include<bits/stdc++.h>
using namespace std;
int main()
{
	long long n,s;
 
	cin >> n>>s;
	
	n %= 10;
	s %= 10;
	cout << n + s;
	return 0;
}

```
## Explanation
the last digit = num%10
last digit in num1 + last digit num2 
## Take Away

