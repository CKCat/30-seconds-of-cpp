# data

**Description** : The function returns a pointer to the first element in the array which is used internally by the vector. It doesn't accept any parameters.

**说明：** 该函数返回一个指向数组中第一个元素的指针，该指针在向量内部使用。它不接受任何参数。

**Example**:

```cpp
    int main(){

    //vector initialisation
    std::vector<int> v = { 1, 2, 3, 4, 5 };
    
    //memory pointer pointing to the first element
    int* pos = v.data(); 
  
    // prints the vector 
    std::cout << "The vector elements are: "; 
    for (int i = 0; i < v.size(); ++i) 
        std::cout << *pos++ << " "; 
  
    return 0;
    }
```
**[Run Code](https://rextester.com/DHEP56251)**
