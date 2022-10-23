# The problem sum them 2
[problem_sum](https://codeforces.com/group/P9uFhztGih/contest/401786/problem/D)
## Hints
single name A ,
 which A contains no more than 10 characters
 
## Solution python
```python
n1,n2 = sorted(map(int, input().split()))
print(n1+n2)
```
## Solution java
```java
import java.util.Scanner;
 
public class Myproject {
 
    public static void main(String[] args) {
         
     Scanner input= new Scanner(System.in);
      
     
     long  s = input.nextLong();
     long m = input.nextLong();
    
       System.out.println(s + m);
        
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
	cout << n+s;
	
	return 0;
}
```
## Explanation
wo numbers A and B , (0 ≤ A,B≤ 10^15).

## Take Away

