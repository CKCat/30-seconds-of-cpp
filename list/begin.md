# begin

**Description** : begin() function is used to return an iterator pointing to the first element of the list container.

**描述**：begin() 函数用于返回一个指向列表容器第一个元素的迭代器。

**Example**:
```cpp
    // declaration of list container 
    std::list<int> mylist{ 1, 2, 3, 4, 5 }; 
  
    // using begin() to print list 
    for (auto it = mylist.begin(); it != mylist.end(); ++it) 
        std::cout << ' ' << *it; 

```
**[Run Code](https://rextester.com/OLYXB49722)**
