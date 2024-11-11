### EX NO : 04
### DATE : 
##  Read a File Name from User and Create that File using fopen()

### AIM :
         To Write a C program to read a file name from user
         and create that file using fopen()
        
### ALGORITHM :
 1. Define a Character Array to Hold the File Name
 2. Input the File Name from the User
 3. Open the File in Write Mode Using fopen()
 4. Check if the File Was Created Successfully
 5. Display the Result
 6. Close the File Using fclose()

### PROGRAM :
```C
#include <stdio.h>
int main()
{
   char name[50];
   scanf("%s",name);
   FILE *fp=fopen("name.html","w");
   if(fp==NULL)
   {
       printf("Null");
       return 0;
   }
   printf("%s File Created Successfully\n",name);
   printf("%s File Opened\n",name);
   fclose(fp);
   printf("%s File Closed",name);
}
```

### OUTPUT :
![4 C A](https://github.com/user-attachments/assets/cc3fd9d1-ba1e-4abf-8d3c-397a65fd60ab)



### RESULT :
          Thus the c program to read a file name from user and create 
          that file using fopen() was executed successfully.
