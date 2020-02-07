# Activity3

Here are the answers for the discusstion questions. 


## Try with a LinkedList - does it make any difference?

As a matter of fact, there is no really big difference between ArrayList and LinkedList, but LinkedList tend to take more time to find an item in a particular location. For this reason, Access to elements in the list is more faster in ArrayList than LinkedList. The reason why ArrayList faster is that it allows random access to the elements in the list as it operates on an Index-based data structure.


## What happens if you use list.remove(Integer.valueOf(77))?

It will remove the first occurrence of the specified element from the list, which in this case the second element.


## What does this method do? list.remove(5);

It removes the object at position 5, which in this case 77.


## Which of the two lists performs better as the size increases?

There are three different cases that we should consider to choose which list performs better. In the case of searching, ArrayList performs better than LinkedList because ArrayList knows each index for each element, but LinkedList has to search for each specific element. in the cases of inserting and removing, LinkedList would be better to use because of the pointers that it uses; whereas, ArrayList requires more memory since it has to shift every time during both cases.
