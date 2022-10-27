# crend

**Description :** The list::crend() is a built-in function in C++ STL that returns a constant reverse iterator which points to the theoretical element preceding the first element in the list i.e. the reverse end of the list. 

**描述：** list::crend() 是 C++ STL 中的内置函数，它返回一个常量反向迭代器，该迭代器指向列表中第一个元素之前的理论元素，即列表的反向端。

**Example** :
```cpp
    // declaration of the list 
    std::list<int> lis = { 27, 46, 65, 84, 30, 22 }; 
  
    std::cout << "List: " << std::endl; 
  
    for (auto it = lis.crbegin(); it != lis.crend(); ++it) 
        std::cout << *it << " "; 

```
**[Run Code](https://rextester.com/MUBAJ40037)**
