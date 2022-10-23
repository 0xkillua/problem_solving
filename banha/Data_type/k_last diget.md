# The problem K. Last Digit
[problem_sum](https://codeforces.com/group/P9uFhztGih/contest/401786/problem/K)

## Solution python
```python
n1=int(input())
n1%=2
if n1==0:
    print(1)
else:
    print(6)

```
## Solution java
```java
import java.util.Scanner;
 
public class Myproject {
 
    public static void main(String[] args) {
         
     Scanner input= new Scanner(System.in);
      
     
   long s = input.nextLong();
        if (s%2==0) {
             System.out.println(1);
        } 
        else {
           System.out.println(6); 
        }  
    }
}

```
## Solution c++
```c++
##include<iostream>
using namespace std;
 
int main()
{ long long x;
 
cin>>x;
if(x%2==0)
cout<<"1";
else
cout<<"6";
 
    return 0;
}
```
## Explanation

## Take Away

