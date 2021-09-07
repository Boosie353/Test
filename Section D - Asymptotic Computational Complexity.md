 Usually, when we talk about time complexity, we refer to Big-O notation. Simply put, the notation describes how the time to perform the algorithm grows with the input size.
 
 ArrayList
add() – takes O(1) time. However, worst-case scenario, when a new array has to be created and all the elements copied to it, is O(n).

Alternatives with their worst case time complexity scenarios

LinkedList
add() – appends an element to the end of the list. So it only updates a tail, therefore O(1) constant-time complexity.

CopyOnWriteArrayList
add() – depends on the position we add value, so the complexity is O(n)