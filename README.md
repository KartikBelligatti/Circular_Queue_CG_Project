# Circular_Queue_CG_Project

Circular Queue is a linear data structure in which the operations are performed based on FIFO (First In First Out) principle and the last position is connected back to the first position to make
a circle. It is also called “Ring Buffer”.

## Operations on Circular Queue
The following are the operations that can be performed on a circular queue:
### Front: It is used to get the front element from the Queue.
###	Rear: It is used to get the rear element from the Queue.
###	enQueue(value): This function is used to insert an element into the circular queue. In a circular queue, the new element is always inserted at Rear position. 
1.	Check whether queue is Full – Check ((rear == SIZE-1 && front == 0) || (rear == front-1)).  
2.	If it is full then display Queue is full. If queue is not full then, check if (rear == SIZE – 1 && front != 0) if it is true then set rear=0 and insert element.
###	deQueue(): This function is used to delete an element from the circular queue. In a circular queue, the element is always deleted from front position. 
1.	Check whether queue is Empty means check (front==-1). 
2.	If it is empty then display Queue is empty. If queue isn’t empty then step 3 will be executed.
3.	Check if (front==rear) if it is true then set front=rear= -1 else check if (front==size-1), if it is true then set front=0 and return the element.

### Installation Process:
1. Download the Zip file from this repository.
2. Extract the file from the Zip folder.
3. Open Microsoft Visual studio (Latest version possible).
4. Open the extracted file from visual studio.
5. Run the .c file to get the output.

## Screenshots
### Introduction page
![image](https://user-images.githubusercontent.com/58390249/179445134-d64c66c1-e726-4d5a-bb7d-eb8e92539c6c.png)

### Help page
![image](https://user-images.githubusercontent.com/58390249/179445175-24761315-e347-40d5-a87b-3eb6e7e1d636.png)

### More Info page
![image](https://user-images.githubusercontent.com/58390249/179445248-adad1915-8ed7-40ed-a8a1-b2b11794139d.png)

### Enqueue operation
![image](https://user-images.githubusercontent.com/58390249/179445269-19e0fe12-571f-4348-92ed-2b43db387e4f.png)

### Queue overflow
![image](https://user-images.githubusercontent.com/58390249/179445300-4e70b878-87b0-4079-84f8-9f59bd6cd961.png)

### Dequeue operation
![image](https://user-images.githubusercontent.com/58390249/179445335-feb9ded6-b9b4-42bd-9508-7363e31876b6.png)

### Queue underflow
![image](https://user-images.githubusercontent.com/58390249/179445361-278ae931-1d8d-4f98-9c65-3f80c85ca5fd.png)

### Enqueue after Dequeue.
![image](https://user-images.githubusercontent.com/58390249/179445411-49533934-f004-40a5-8fef-46471becbf56.png)

### Display menu
![image](https://user-images.githubusercontent.com/58390249/179445433-11cef315-5eaf-4d55-8d9e-ac3f5599329c.png)


