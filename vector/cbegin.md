# cbegin

**Description** : The function returns an iterator which is used to iterate container.

Notes:

1. The iterator points to the beginning of the vector.
2. Iterator cannot modify the contents of the vector.

**说明：** 该函数返回一个用于迭代容器的迭代器。

注意：
1. 迭代器指向向量的开头。
2. 迭代器不能修改向量的内容。

**Example**:
```cpp
// Demonstrates cbegin() 
#include <iostream>
#include <vector>

int main(){
    //declares an empty vector
    std::vector<int> vec;
    
    //inserting elements in vector
    vec.push_back(101);
    vec.push_back(12);
    vec.push_back(999);
  
    //Displaying elements of  vector
    std::cout << "Content of the vector \n";
    for (auto it = vec.cbegin(); it != vec.end(); ++it){ 
        std::cout << *it << '\n'; 
    }
    return 0;
}

```
**[Run Code](https://rextester.com/XRFTW94461)**

