2.1
Lists have a smaller run time for insertion operations than arrays do, so a list data structure will be best at this case. Furthermore, each item on the list will be read every month, so a list structure will perform well in comparison to an array for read operations

2.2
Because linked lists are better for insertions and deletions, a linked list would be the more appropriate data structure to use here. If you used an array, the entire array would have to be reallocated to a new slot in memory each time a new order was added to the beginning of the queue. Moreover, because the chef is always taking the first item off the queue, random access (which arrays are better suited for) isn't a requirement.
