# empty

**Description :** The vector::empty() is a built-in function in C++ STL is used to check whether a particular vector container is empty or not. 

**说明：** vector::empty() 是 C++ STL 中的内置函数，用于检查特定向量容器是否为空。

**Example** :
```cpp
    // Creating a vector 
    std::vector<int> example; 
  
    // check if vector is empty 
    if (example.empty()) 
        std::cout << "Empty Vector\n"; 
    else
        std::cout << "Not Empty\n"; 
  
    // Add elements to the Vector 
    example.push_back(10); 
    example.push_back(20); 
    example.push_back(30); 
    example.push_back(40); 
  
    // check again if vector is empty 
    if (example.empty()) 
        std::cout << "Empty Vector\n"; 
    else
        std::cout << "Not Empty\n"; 
         
```
**[Run Code](https://rextester.com/ZMFKZ74225)**
