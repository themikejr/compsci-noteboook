#####
Queue
#####

* Insert at the "end" pull from the "beginning"
* First in, First out (FIFO)

Interface
=========

* enqueue()
* dequeue()

Implementations
===============

Using an Array
--------------
* Con: if you don't know size this could be costly
* Con: if large, traversing to find start/end could be costly

Using a Linked List
-------------------
* Pro: Don't need to know size
* Pro: Can store pointer to start/end

Examples
========
