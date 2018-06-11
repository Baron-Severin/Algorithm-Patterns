# Runner

##### Time Efficiency: O(N)
##### Space Efficiency: O(1)
##### Use Case:
Iterate over a collection of unknown length (usually a [SLL](https://en.wikipedia.org/wiki/Linked_list#Singly_linked_list)), find item N before end

##### Description
Create two references to the head of the collection, `fast` and `slow`.  Assign `fast` to `fast.next` N times.  Then, assign both `fast` and `slow` to their respective `next` properties until reaching the end of the collection.  `slow` will now be on the required item.
