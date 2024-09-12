TestIterator.java
1. //TODO what happens if you use list.remove(Integer.valueOf(77))?
   Task :test FAILED
   cs271.lab.list.TestIterator > testRemove FAILED
       java.util.ConcurrentModificationException at TestIterator.java:78
2. //TODO also try with a LinkedList - does it make any difference?
    Both compile, however the linked list implementation is slightly slower

TestList.java
3.// list.remove(Integer.valueOf(5)); // what does this one do?
    This removes the first occurence of the integer 5 in the list rather than the element at index 5
4.// TODO also try with a LinkedList - does it make any difference?
    Both compile, however, the linked list implementation is slightly faster

TestPerformance.java
5.// TODO run test and record running times for SIZE = 10, 100, 1000, 10000, ...
  // which of the two lists performs better as the size increases?
    For the ListAddRemove methods the linked list performed better as SIZE grew
    For the ListAccess methods the Array list outperformed the linked list every time
    When SIZE = 10000000 all methods failed with the following error "java.lang.OutOfMemoryError: Java heap space"