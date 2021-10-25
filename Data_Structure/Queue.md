How to implement a queue in Python

Queue is a linear data structure that stores items in a First-In/First Out(FIFO) manner. In queue, the data element that is inserted first will be removed first.

Operations that can be performed on the queue are:

Enqueue: It adds an item to the queue. If the queue is full, then it is said to be an Overflow condition.

Dequeue: It removes an item from the queue. The items are popped in the same order in which they are pushed. If the queue is empty, then it is said to be an Underflow condition.

Front: It gives the front item from the queue.

Rear: It gives the last item from the queue.

# Implementing Queue using List :
```python
q=[]
q.append(10)
q.append(100)
q.append(1000)
q.append(10000)
print("Initial Queue is:",q)
print(q.pop(0))
print(q.pop(0))
print(q.pop(0))
print("After Removing elements:",q)
```
