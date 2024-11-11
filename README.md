### EX NO : 02
### DATE : 
##  Display Area of Square using Pointer to Structure

### AIM :
         To Write a C program to display area of square using pointer to structure
        
### ALGORITHM :

 1. Define a Structure to Hold the Side Length of the Square
 2. Define an Input Function to Get the Side Length Using a Pointer to the Structure
 3. Define a Calculation Function to Compute the Area of the Square Using Pointer Dereferencing
 4. Write the Main Function to Control the Flow of the Program
 5. Display the result.

### PROGRAM :
```C
#include<stdio.h>
struct area{
    int num;
    int aval;
};

int main(){
    struct area *areaptr, area1;
    areaptr=&area1;
    scanf("%d",&areaptr->num);
    areaptr->aval=(areaptr->num)*(areaptr->num);
    printf("Displaying:\nArea: %d",areaptr->aval);
    
 return 0;

}

```

### OUTPUT :
![2 c b](https://github.com/user-attachments/assets/e83760ee-97b1-4d97-a47b-c3218d5dded9)


### RESULT :
        Thus the c program to display area of square using pointer 
        to structure was executed successfully.
        
