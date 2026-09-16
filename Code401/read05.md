## Linked Lists: A Quick Cheat Sheet

One concept I learned from these readings is how **linked lists organize data differently from arrays**. A helpful analogy is to think of a linked list like a **treasure hunt**. Each clue represents a **node**, and instead of knowing where every clue is located ahead of time, each clue tells you where to find the next one.

### What is a Linked List?

A linked list is a data structure made up of **nodes connected to one another**. Each node contains a value and a reference called `Next`, which points to the next node. The first node is referenced by the `Head`.

A singly linked list can be visualized like this:

`Head → [10 | Next] → [20 | Next] → [30 | Next] → NULL`

`NULL` tells us that we have reached the end of the list.

### Important Vocabulary

* **Node:** An individual item in a linked list that stores data.
* **Head:** A reference to the first node.
* **Next:** A reference that tells us where the next node is.
* **Current:** A temporary reference used to keep track of the node we are currently visiting.
* **Singly Linked List:** Each node points only to the next node.
* **Doubly Linked List:** Each node can reference both the next and previous nodes.

### How Do We Move Through a Linked List?

Unlike an array, we don't jump directly to an index. Instead, we start at the `Head` and follow each node's `Next` reference.

For example:

`Head → Apple → Banana → Orange → NULL`

If I am searching for **Orange**, I start with Apple, follow its `Next` reference to Banana, and then follow Banana's `Next` reference to Orange.

This process is called **traversal**. A `while` loop is useful because we can continue moving through the nodes until `Current` becomes `NULL`.

### Why Does Big O Matter?

Big O helps us describe how efficient an algorithm is as the amount of data increases. We can examine both **time complexity**, or how much work an algorithm performs, and **space complexity**, or how much memory it requires.

For example, searching through a linked list has a worst-case time complexity of **O(n)** because the value we want could be the final node. If there are 100 nodes, we might have to check all 100.

However, adding a new node to the **beginning** can be **O(1)**. We only need to make the new node point to the old `Head` and then change `Head` to point to our new node. The number of existing nodes doesn't change the amount of work required.

### My Main Takeaway

The biggest thing I learned is that linked lists depend heavily on **references**. The nodes don't need to be stored next to each other because each node knows where the next one is. The order in which references are changed is also important—changing the wrong reference too early could break the chain and cause us to lose access to part of the list.

So, in my treasure-hunt analogy: **don't throw away your current clue until you've written down where the next clue is!**
