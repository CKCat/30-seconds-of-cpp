# cend

**Description** : The function returns an iterator which is used to iterate container.

Notes:

1. The iterator points to past-the-end element of the vector.
2. Iterator cannot modify the contents of the vector.

**说明：** 该函数返回一个用于迭代容器的迭代器。

注意：
1. 迭代器指向向量的末尾元素。
2. 迭代器不能修改向量的内容。

**Syntax :** vectorname.cend()

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
    vec.push_back(143);
  
    //Displaying elements of  vector from the end
    std::cout << "Content of the vector \n";
    for (auto it = vec.cend() - 1;  it >= vec.begin(); --it){ 
        std::cout << *it << '\n'; 
    }
    return 0;
}

```
**[Run Code](https://rextester.com/QQMCH84623)**

