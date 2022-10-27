# clear

**Description** : clear() function is used to remove all the elements of the list container, thus making it size 0.

**说明** : clear() 函数用于删除列表容器的所有元素，从而使其大小为 0。

**Example**:
```cpp

    std::list<int> mylist{ 1, 2, 3, 4, 5 }; 
  
    mylist.clear(); 
    // List becomes empty 
  
    // Printing the list 
    for (auto value : mylist) {
        std::cout << ' ' << value;  
    }
 
```
**[Run Code](https://rextester.com/IKAFZ38505)**
