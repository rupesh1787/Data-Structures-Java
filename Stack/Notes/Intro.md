🧱 Stack in Java (Quick Notes)

Stack → follows LIFO (Last In, First Out) rule.

Used to store elements where the last added item comes out first.

Main operations:

push() → add item

pop() → remove top item

peek() → check top item

isEmpty() → check if stack is empty

Ways to implement:

Using Array / ArrayList → simple, fixed or dynamic size.

Using LinkedList → flexible size, no overflow.

Using Java’s built-in Stack class (java.util.Stack) → easy to use.

Using Deque (ArrayDeque) → modern and faster approach.

All main operations: O(1) time.

Used in: undo-redo, expression evaluation, recursion, backtracking, etc.
