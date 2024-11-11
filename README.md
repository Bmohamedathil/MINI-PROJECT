### EX NO : 03 
### DATE : 
## Read a File Name from User and Create that File and Insert Text in to that File

### AIM :
        To Write a C program to read a file name from user, create that file and insert 
        text in to that file
        
### ALGORITHM :

1. Define a Character Array to Hold the File Name

2. Input the File Name from the User

3. Open the File in Write Mode Using fopen()
   
4. Define a Character Array to Hold the Text to Insert
   
5. Input the Text to be Inserted
 
6. Write the Text to the File
 
7. Close the File Using fclose()
 
8. Display a Confirmation Message
 
9. Display the result.

### PROGRAM :
```C
#include <stdio.h>
int main()
{
    char name[50];
    scanf("%s",name);
    
    FILE *fp=fopen("name.txt","w");
    if(name==NULL)
    {
        printf("NULL");
    }
    fprintf(fp,"2\naaa\nbbb");
    
    fclose(fp);
    printf("%s Opened\n",name);
    printf("Data added Successfully");
        
}
```

### OUTPUT :
![image](https://github.com/user-attachments/assets/bb623b47-222a-4c18-b0f5-9b376e357a7c)


### RESULT :
        Thus the c program to read a file name from user, create that file and insert text in to 
        that file was executed successfully.
