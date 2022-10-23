# The problem G. Math
[problem_sum](https://codeforces.com/group/P9uFhztGih/contest/401786/problem/G)
## Hints
single name A ,
 which A contains no more than 10 characters
 
## Solution python
```python
n1,n2 = (map(int, input().split()))
print(n1,"+",n2,"=",(n1+n2))
print(n1,"-",n2,"=",(n1-n2))
print(n1,"*",n2,"=",(n1*n2))
print(n1,"/",n2,"=",int(n1/n2))
print(n1,"%",n2,"=",(n1%n2))
```
## Solution java
```java
import java.util.Scanner;
 
public class Myproject {
 
    public static void main(String[] args) {
         
     Scanner input= new Scanner(System.in);
      
     
    long s = input.nextLong();
     long m = input.nextLong();
    
       System.out.println(s +" + "+m+" = "+(s+m));
        System.out.println(s +" - "+m+" = "+(s-m));
         System.out.println(s +" * "+m+" = "+s*m);
          System.out.println(s +" / "+m+" = "+s/m);
           System.out.println(s +" % "+m+" = "+s%m);
        
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
	
	cout << n << " + " << s <<" = "<< n + s << endl;
	cout << n << " - " << s << " = " << n - s<<endl;
	cout << n << " * " << s << " = " << n * s << endl;
	cout << n << " / " << s << " = " << n / s << endl;
	cout << n << " % " << s << " = " << n % s << endl;
	return 0;
}
```
## Explanation

## Take Away

