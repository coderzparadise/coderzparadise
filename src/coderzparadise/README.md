#### Instructions (How To Get Started)

1. Install **pip** package in your terminal (command prompt):
```
pip install coderzparadise
```
2. Use the examples below in your code :)

3. Done!

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
**11** | Trie | Trie()

---

# Code Examples:
### 0. Binary Search Tree
[UML](https://github.com/coderzparadise/DataStructure/tree/main/BinarySearchTree)
```
from coderzparadise import DataStructure

b = DataStructure.BST()

b.insert(50)
b.insert(75)
b.insert(25)
b.insert(100)
b.insert(95)

b.display()
```


### 1. DisjointForrestSet
[UML](https://github.com/coderzparadise/DataStructure/tree/main/DisjointForrestSet)
```
from coderzparadise import DataStructure

d = DataStructure.DSF(10) #parameter: (integer) 10 is setting size of disjointforrestset.

d.insert(0, 1)
d.insert(0, 3)
d.insert(0, 5)
d.insert(0, 7)
d.insert(0, 9)
d.insert(2, 4)
d.insert(2, 6)

number_of_sets_found = d.num_of_sets()
print('dsf num of sets: ', number_of_sets_found,\n)

d.display()
```

### 2. Graph - Adjacency List
[UML](https://github.com/coderzparadise/DataStructure/tree/main/Graph)
```
from coderzparadise import DataStructure

a = DataStructure.AdjacencyList([0,1,2,3,4,5,6,7,8,9]) #parameter: list is nodes that make up the graph.

a.insert(9, 1)
a.insert(9, 2)
a.insert(9, 3)
a.insert(9, 4)
a.insert(0, 5)
a.insert(0, 3)

a.display()
```

### 3. Graph - Adjacency Matrix
[UML](https://github.com/coderzparadise/DataStructure/tree/main/Graph)
```
from coderzparadise import DataStructure

a = DataStructure.AdjacencyMatrix([0,1,2,3,4,5,6,7,8,9]) #parameter: list is nodes that make up the graph.

a.insert(9, 1)
a.insert(9, 2)
a.insert(9, 3)
a.insert(9, 4)
a.insert(0, 5)
a.insert(0, 3)

a.display()
```

### 4. Graph - EdgeList
[UML](https://github.com/coderzparadise/DataStructure/tree/main/Graph)
```
from coderzparadise import DataStructure

e = DataStructure.AdjacencyMatrix([0,1,2,3,4,5,6,7,8,9]) #paramter: list is nodes that make up the graph.

e.insert(9, 1)
e.insert(9, 2)
e.insert(9, 3)
e.insert(9, 4)
e.insert(0, 5)
e.insert(0, 3)

e.display()
```

### 5. Hash Map
[UML](https://github.com/coderzparadise/DataStructure/tree/main/HashMap)
```
from coderzparadise import DataStructure

h = HashMap(2) #parameter: (integer) 2 is setting up the inital size of hashmap.

h.insert('soccer')
h.insert('soccer')
h.insert('basketball')
h.insert('pizza')
h.insert('hamburger')

h.display()
```

### 6. Heap
[UML](https://github.com/coderzparadise/DataStructure/tree/main/Heap)
```
from coderzparadise import DataStructure

h = Heap()

h.insert(16)
h.insert(16)
h.insert(37)
h.insert(28)
h.insert(49)
h.insert(21)
h.insert(5)

h.display()
```


### 7. Linked List
[UML](https://github.com/coderzparadise/DataStructure/tree/main/LinkedList)
```
from coderzparadise import DataStructure

ll = DataStructure.LinkedList()

ll.insert(75)
ll.insert(75)
ll.insert(80)
ll.insert(81)
ll.insert(99)
ll.insert(2)
ll.insert(77)

ll.display()
```

### 8. Queue
[UML](https://github.com/coderzparadise/DataStructure/tree/main/Queue)
```
from coderzparadise import DataStructure

q = DataStructure.Queue()

q.insert(10)
q.insert(10)
q.insert(20)
q.insert(30)
q.insert(40)
q.insert(50)

q.display()
```

### 9. Set
[UML](https://github.com/coderzparadise/DataStructure/tree/main/Set)
```
from coderzparadise import DataStructure

s = DataStructure.Set()

s.insert(10)
s.insert(10)
s.insert(20)
s.insert(50)
s.insert(50)
s.insert(50)
s.insert(50)
s.insert(30)

s.display()
```

### 10. Stack
[UML](https://github.com/coderzparadise/DataStructure/tree/main/Stack)
```
from coderzparadise import DataStructure

s = DataStructure.Stack()

s.insert(10)
s.insert(10)
s.insert(20)
s.insert(30)
s.insert(40)
s.insert(50)

s.display()
```


### 11. Trie
[UML](https://github.com/coderzparadise/DataStructure/tree/main/Trie)
```
from coderzparadise import DataStructure

t = DataStructure.Trie()
t.insert("socks")
t.insert("soccer")
t.insert("colors")
t.search_word("sock")
t.search_word("socks")
t.is_prefix("b")
t.is_prefix("s")
```
