### EX NO : 01
### DATE : 
##  Find the Biggest among Three Numbers

### AIM :
         To Write a C program to find the biggest among three numbers using structure
        
### ALGORITHM :
 1. Define a structure to hold three integers.
 2. Create a function to find the largest number among the three.
 3. Input the numbers from the user.
 4. Compare the numbers inside the function and return the largest one.
 5. Display the result.

### PROGRAM :
```C
#include<stdio.h>
struct big
{
    int a,b,c;
}s;
int main()
{
    scanf("%d %d %d",&s.a,&s.b,&s.c);
    if(s.a > s.b && s.a > s.c)
    printf("%d",s.a);
    else if(s.b > s.a && s.b > s.c)
    printf("%d",s.b);
    else
    printf("%d",s.c);
}
```

### OUTPUT :
![1C A](https://github.com/user-attachments/assets/fa4ff4e7-34c3-47c5-b629-6cf44a3946fc)


### RESULT :
          Thus the c program to write a C program to find the biggest among 
          three numbers using structure was executed successfully.
