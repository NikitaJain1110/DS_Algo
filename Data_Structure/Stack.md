#Stack in Python
In this tutorial, we will learn the basics of the stack and implement it using the Python code.

What is a Stack?
A stack is a linear data structure where data is arranged objects on over another. It stores the data in LIFO (Last in First Out) manner. The data is stored in a similar order as plates are arranged one above another in the kitchen. The simple example of a stack is the Undo feature in the editor. The Undo feature works on the last event that we have done.

We always pick the last plate from the stack of the plate. In stack, the new element is inserted at the one end and an element can be removed only that end.

We can perform the two operations in the stack - PUSH and POP. The PUSH operation is when we add an element and the POP operation is when we remove an element from the stack.

```python
# initial empty stack  
my_stack = []  
  
# append() function to push   
# element in the my_stack   
my_stack.append('x')  
my_stack.append('y')  
my_stack.append('z')  
 
print(my_stack)  
  
# pop() function to pop   
# element from my_stack in    
# LIFO order   
print('\nElements poped from my_stack:')  
print(my_stack.pop())  
print(my_stack.pop())  
print(my_stack.pop())  
  
print('\nmy_stack after elements are poped:')  
print(my_stack)   
```
