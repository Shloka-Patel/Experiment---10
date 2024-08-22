# Experiment---10 

### Aim 

### Theory 

### Code 

(A) <br> 
```
// Printing the values by using callby value 

#include<iostream> 
using namespace std; 
void swap(int x, int y) 
{
    int swap;
    swap=x;
    x=y;
    y=swap;
}

int main() 
{
    int a=4, b=7;
    swap(a,b);
    cout<<"Value of a is: "<<a<<"\n";
    cout<<"Value of b is: "<<b<<"\n";
    return 0;
}

```

(B) <br> 
```
// Swapping the values 

#include<iostream> 
using namespace std; 
void swap(int *x, int *y) 
{
    int *swap;
    swap=x;
    x=y;
    y=swap;
}

int main() 
{
    int a=4,b=7;
    swap(a,b);
    cout<<"Value of a is: "<<a<<"\n";
    cout<<"Value of b is: "<<b<<"\n";
    return 0;
} 
```

(C) <br> 
```
```

### Output 

(A) <br> 
![](https://github.com/Shloka-Patel/Experiment---10/blob/main/Output_10A.png) 

(B) <br> 
![](https://github.com/Shloka-Patel/Experiment---10/blob/main/Output_10B.png) 

(C) <br> 
![]() 

### Conclusion 
