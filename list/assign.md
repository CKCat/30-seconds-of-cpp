# assign

**Description** :The list::assign() is a built-in function in C++ STL which is used to assign values to a list.

3
**描述** :list::assign()是C++ STL中的一个内置函数，用来给一个列表赋值。

**Example**:
```cpp
    // Initialization of list 
    std::list<int> demo_list; 
  
    // Assigning the value 100, 5 times 
    // to the list, list_demo. 
    demo_list.assign(5, 100); 
  
    // Displaying the list 
    for (int itr : demo_list) { 
        std::cout << itr << " "; 
    } 

```
**[Run Code](https://rextester.com/UMFNZM11115)**
