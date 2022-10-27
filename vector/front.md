# front

**Description** :The vector::front() is a built-in function in C++ STL which is used to return a reference to the first element in a vector container.

**说明：** vector::front() 是 C++ STL 中的内置函数，用于返回对向量容器中第一个元素的引用。

**Example**:
```cpp
    // Creating a vector 
    std::vector<int> example; 
  
    // Add elements to the List 
    example.push_back(10); 
    example.push_back(20); 
    example.push_back(30); 
    example.push_back(40); 
  
    // get the first element using front() 
    int & ele = example.front(); 
  
    // Print the first element 
    std::cout << ele; 
 
```
**[Run Code](https://rextester.com/WASUB54049)**
