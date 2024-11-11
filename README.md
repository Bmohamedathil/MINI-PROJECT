### EX NO : 12
### DATE : 
##  Insert Elements in Queue using Array.
### AIM :
         To Write a C program to insert elements in queue using array.
         
### ALGORITHM :

 1. Define Queue Properties
 2. Initialize the Queue (if necessary)
 3. Check if Queue is Full
 4. Check if Queue is Empty
 5. Insert the Element at the Rear
 6. End the Function
### PROGRAM :
```C
char queue[50];
int front,rear;
void enqueue(char data)
{
    if(front==-1&&rear==-1)
    {
        front=rear=0;
        queue[rear]=data;
    }
    else
    {
        rear++;
        queue[rear]=data;
        
    }
}
```

### OUTPUT :
![image](https://github.com/user-attachments/assets/363935b6-aa2c-4f47-b88f-77b32e0a7c0d)

### RESULT :
          Thus the c program to insert elements in queue using array was executed successfully.
