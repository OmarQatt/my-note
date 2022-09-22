# Stack & Queue

## Stack is a container of objects that are inserted and removed according to the last-in first-out (LIFO) principle.

## Queue is a container of objects (a linear collection) that are inserted and removed according to the first-in first-out (FIFO) principle.

| Stack  | queue |
| ------------- | ------------- |
| Insertion and deletion in stacks takes place only from one end of the list called the top  | Insertion and deletion in queues takes place from the opposite ends of the list. The insertion takes place at the rear of the list and the deletion takes place from the front of the list  |
| Insert operation is called push operation.	  | Insert operation is called enqueue operation.  |
| Delete operation is called pop operation.	  | Delete operation is called dequeue operation.  |

# Stack is a container of objects that are inserted and removed according to the last-in first-out (LIFO) principle.

As stated earlier, we can take Stacks like a pile of plates, each plate placed on top of each other. The first plate that is placed becomes the last to be removed.
In the image above, the push adds an element to the Stack while pop removes the available on top. Push and Pop are the basic operations carried out on Stacks.
![1_-EyTW6ktTIS2oY2ysa8VsQ](https://user-images.githubusercontent.com/65464415/191665394-1ca286d1-56e8-4c3a-8f75-f02e62da9a25.png)

push — inserts into the stack.
pop — deletes from the stack.
Other operations are also available but their functionality is to check the status of the Stack, unlike the insertion and deletion operations. And they are;

isFull — checks if the stack is full.
isEmpty — checks if the stack is empty.
peek — gets the element at the top of the Stack.

#  Queue is a container of objects (a linear collection) that are inserted and removed according to the first-in first-out (FIFO) principle.

There are two basic operations used by Queues. These operations involve only adding data to the queue — the first data will also initialize the Queue before it gets added to it, while the second operation removes data from the Queue. 
Enqueue — adds an item to the queue.
Dequeue — removes an item from the queue.
Just like Stack, we also have a few more operations, they do not manipulate or move the data but check the status of the Queue.

Peek — gets the data at the front of the Queue.
isEmpty — checks if the memory(Queue) is empty.
isFull — checks if the memory is full.

