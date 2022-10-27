# cend

**Description** : The list::cend() is a built-in function in C++ STL which returns a constant random access iterator which points to the end of the list. 

**描述**：list::cend() 是 C++ STL 中的内置函数，它返回一个指向列表末尾的常量随机访问迭代器。

**Example**:
```cpp
    // declaration of list 
    std::list<int> lis = { 100, 200, 300, 400, 500 }; 
  
    // printing list elements 
    std::cout << "List: " << std::endl; 
  
    for (auto it = lis.cbegin(); it != lis.cend(); ++it) 
        std::cout << *it << " "; 

```
**[Run Code](https://rextester.com/QTRH25197)**
