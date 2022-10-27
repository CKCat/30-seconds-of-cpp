# find

**Description :** The map::find() is a function which returns an iterator through which the key and value pair can be accessed. If not found the iterator returns map.end() 

描述： map::find() 是一个函数，它返回一个迭代器，通过该迭代器可以访问键和值对。如果没有找到，迭代器返回 map.end()

**Example** :

```cpp
// Demonstrates find() 
#include <iostream>
#include <map> 
  
int main() { 
    // declaration of map container
    std::map<int, int> mymap;
    mymap[0] = 10;
    mymap[1] = 11; 
    mymap[2] = 12; 
    mymap[3] = 13; 

    // using find() function
    auto itr = mymap.find(1);
    std::cout << "The value at position " << itr->first << " is " << itr->second << "\n";
    return 0; 
} 
```
**[Run Code](https://rextester.com/TNMP46907)**
