1. //TODO what happens if you use list.remove(Integer.valueOf(77))?
   Task :test FAILED
   cs271.lab.list.TestIterator > testRemove FAILED
       java.util.ConcurrentModificationException at TestIterator.java:78
2. //TODO also try with a LinkedList - does it make any difference?
    Both compile, however the linked list implementation is slightly slower
3.// list.remove(Integer.valueOf(5)); // what does this one do?
    This removes the first occurence of the integer 5 in the list rather than the element at index 5
