# back

**Description :** 

Returns a reference to the last element in the vector

**描述 ：**

返回对向量中最后一个元素的引用。

**Example** :

```cpp
    // Initialize int vector
    std::vector<int> myVector = {1, 2, 3, 4, 5}; 
    
    // Save reference to the last element
    int& lastEle = myVector.back();
  
    // Last element is 5
    std::cout << myVector.back() << " ";
    
    // Change the last element by changing the reference variable lastEle
    lastEle = 10;
  
    // Last element is 10
    std::cout << myVector.back() << " ";
    
```
**[Run Code](https://rextester.com/RQEY20725)**
