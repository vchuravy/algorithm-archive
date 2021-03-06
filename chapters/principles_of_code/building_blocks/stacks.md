### Stacks and Queues

Stacks and Queues are two sides of the same coin in computer science. They are both simple data structures that hold multiple elements, but allow you to use a single element at a time. The biggest difference between the two structures is the order in which you can access the elements in the data structure.

In *stacks*, data follows *Last In, First Out* (LIFO), which basically means that whichever element you put in last will be the first element you take out. It acts exactly like a stack in real life. If you put a book on a stack of other books, the first book you will look at when sifting through the stack will be the book you just put on the stack.

In *Queues*, data follows *First In, First Out* (FIFO), which means that whichever element you put in first will be the first element you take out. Imagine a queue of people. It would be unfair if the first person in line for groceries were not the first person to receive attention once the attendant finally shows up.

For the most part, though, queues and stacks are treated the same way. There must be a way to:
1. look at the first element (`top()`)
2. to remove the first element (`pop()`)
3. to push elements onto the data structure (`push()`)

The notation for this depends on the language you are using. Queues, for example, will often use `dequeue()` instead of `pop()` and `front()` instead of `top()`. You will see the language-specific details in the source code under the algorithms in this book, so for now it's simple important to know what stacks and queues are and how to access elements held within them.
