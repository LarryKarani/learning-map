# Memory Management

## Skill Description:

A fellow is able to speed up memory operations, reduce fragmentations in an application and write better python programs 
using Garbage Collection.

# Output:

**Task:** Carry out the following tasks:
* Write a function to allocate the I/O buffer from the Python heap.
* Write functions aimed at handling raw memory blocks from the Python heap.
* Write a function to Load data to a numpy array using pickle.
* Write codes to trigger garbage collection manually and automatically


### Knowledge: 
| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| The size of basic python objects | [ ] | [ ] |
| How Python manages its memory internally. | [ ] | [ ] |
| What is Pickle? | [ ] | [ ] |
| Implement the reference counting algorithm | [ ] | [ ] |
| Run garbage collection process | [ ] | [ ] |
| Management of the Python heap | [ ] | [ ] |



### Behaviours:
| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** If your program has intensive workload and requires low latency, **Action:** you should avoid reference cycles as possible. | [ ] | [ ] | 
| **Context:** Do not force collect garbage too many times. This is because even if you are freeing the memory, **Action:**  it still takes time to evaluate an object’s eligibility for being Garbage collected.| [ ] | [ ] |
| **Context:** If you want to manually manage the Garbage Collection in your application,, **Action:** start doing it only after the app has completely started and then continue doing so in steady operations.| [ ] | [ ] | 



### Beliefs:
| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Everything in Python is an object. | [ ] | [ ] |
| Memory management in Python involves a private heap containing all Python objects and data structures. The management of this private heap is ensured internally by the Python memory manager. | [ ] | [ ] |


### Resources:

- [Memory Management in Python](https://rushter.com/blog/python-memory-managment/)
- [Garbage Collection in Python](https://rushter.com/blog/python-garbage-collector/)
- [Python Memory Management](http://deeplearning.net/software/theano/tutorial/python-memory-management.html)
- [Python Garbage Collection](https://www.journaldev.com/17927/python-garbage-collection-gc)
