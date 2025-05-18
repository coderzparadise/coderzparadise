# Data Structure
Organized way to store and manage data.

Index | Data Structure | Class Name
--- | --- | ---
**0** | Binary Search Tree | BST()
**1** | Disjoint Forrest Set | DSF(int::size)
**2** | Graph - Adjacency List | AdjacencyList(list::nodes)
**3** | Graph - Adjacency Matrix | AdjacencyList(list::nodes)
**4** | Graph - Edge List | EdgeList(list::nodes)
**5** | HashMap | HashMap(int::size)
**6** | Heap | Heap()
**7** | LinkedList | LinkedList()
**8** | Queue | Queue()
**9** | Set | Set()
**10** | Stack | Stack()
**11** | Trie() | Trie()


# How To Use Examples

1. pip install coderzparadise

2. Use examples below to get started

### Linked List
```
from coderzparadise import DataStructure

ll = DataStructure.LinkedList()
ll.insert(75)
ll.insert(80)
ll.insert(81)
ll.display()
```
### Graph - Edge List
```
from coderzparadise import DataStructure

e = DataStructure.EdgeList(["A", "B", "C", "D", "E", "F"])
e.insert("C","D")
e.insert("A","B")
e.display()
```
