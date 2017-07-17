# STACK

The stack data structure can be implemented in two ways:  
1. Assume the last item on the list is the top of the stack. [view](https://github.com/khwilo/python-data-structures/blob/master/Stack/implementation_1.py)  
2. Assume the top of the stack is at the beginning of the list.[view](https://github.com/khwilo/python-data-structures/blob/master/Stack/implementation_2.py)


With this implementations we can see the use of abstraction at work. The performance of the various implementations is a difference. The operations `append()` and `pop()` are both `O(1)`. This means that the [**first implementation**](https://github.com/khwilo/python-data-structures/blob/master/Stack/implementation_1.py) will perform the push and pop operations in constant time regardles of how many items are on the stack. The `insert(0)` and `pop(0)` in the [**second implementation**](https://github.com/khwilo/python-data-structures/blob/master/Stack/implementation_2.py) are both `O(n)` for a stack of size **n**.
