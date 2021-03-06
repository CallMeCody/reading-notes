### CLASS 05


## LYNKED LIST



#### What's a Linked List?

 - A linked list is alinear data structure similar to an array but unlike arrays
 elemets are not stored in a particular index rather each element is a separate 
 object that contains a pointer or a link to the next object to the list.

 - Each element commonly called nodes have two items the data stored and the link
 to the next node or element


 - The entry point to a linked list is called the head. The head is a reference to the first node in the linked list and  the last node on the list points to null. If a list is empty, the head is a null.

  *In javascript linked list looks like this:*

  `````bash
  const list = {
    *head*: {
        value: wonde
        next: {
            value: nes                                           
            next: {
                value: seid
                next: {
                    value: john
                    next: *null*	
                    }
                }
            }
        }
    }
};


`````


### LInked list Advantages

- Elements or nodes are easily to delete or to add without reorganizing
the entire data structure


### Linked list Disadvatages

- search operations are slow
- no random access of elemnts or nodes
- memory space


### Types of Linked List:


- ``` Singly Linked Lists ``` each node contains only one pointer to the next node.

- ``` Doubly Linked Lists ``` each node contains two pointers one pointer to the     next node and one pointer to the previous one

- ``` Circular Linked Lists ``` circular linked lists are a variation of a linked list in which the last node points to the first node or any other node before it thereby forming a loop.


### Linked List Methods:

- ``` size() ``` it returns the number of nodes present in the linked list

- ``` clear() ``` it empties out the list in the linked list

- ``` getLast() ``` it returns the last node in the linked list

- ``` getFirst() ``` it returns the first node in the linked list


 - [freecodecamp](https://www.freecodecamp.org/news/implementing-a-linked-list-in-javascript/)

