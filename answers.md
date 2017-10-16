Why does `LinkedStack` not require an explicit constructor?
We don't need a explicit constructor because push essentially creates each node as items are added, additionally it is connecting them for us.

What is the time and (extra) space complexity of each of the `LinkedStack` methods, as well as `ReverseLines.main`?


How else (not using `Node`) could we have implemented `LinkedStack` in such a way that it is still based on a linked list but the `asList` method uses constant time and space?
By using an array list we can create a LinkedStack without using node because the values are stored starting at 0 and we push the last value added going down towards zero.
By using an array list we will be constantly be using asList method.

Is it better for `push` and `pop` to return the item or the stack itself?
Since pop doesn't require any input and there is no item, it has to return the stack itself. There is no point to create a holder for the item to return it when you can just return the stack.
While push uses the item so it easier to understand what it added to the stack.