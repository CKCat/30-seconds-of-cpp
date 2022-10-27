# lower_bound

**Description**: The function returns an iterator pointing to the key in the map container which is equivalent to k passed in the parameter. 
In case k is not present in the map container, the function returns an iterator pointing to the immediate next element 
which is just greater than k. If the key passed in the parameter exceeds the maximum key in the container, 
then the iterator returned points to number of elements in the map as key and element = 0. 

描述：该函数返回一个迭代器，该迭代器指向map容器中的key，该key等效于参数中传递的k。如果k在map容器中不存在，则该函数将返回一个迭代器，该迭代器指向直接的下一个元素，该元素大于k。如果参数中传递的key超过容器中的最大key，则迭代器返回的点为映射中的元素数量为键和元素= 0。

**Example**:
```cpp
#include <iostream> 
#include <map>
  
int main() { 
  
    // initialize container 
    std::map<int, int> mp; 
  
    // insert elements in random order 
    mp.insert({ 2, 200 }); 
    mp.insert({ 1, 100 }); 
    mp.insert({ 5, 500 }); 
    mp.insert({ 4, 400 }); 
   
  
    // when 1 is present 
    auto it = mp.lower_bound(1); 
    std::cout << "The lower bound of key 1 is "; 
    std::cout << (*it).first << " " << (*it).second << std::endl;  //Prints "The lower bound of key 1 is 1  100"
  
    // when 3 is not present 
    // points to next greater after 3 
    it = mp.lower_bound(3); 
    std::cout << "The lower bound of key 3 is "; 
    std::cout << (*it).first << " " << (*it).second;   //Prints "The lower bound of key 4 is 4  400"
  
    // when 6 exceeds 
    it = mp.lower_bound(6); 
    std::cout << "\nThe lower bound of key 6 is "; 
    std::cout << (*it).first << " " << (*it).second;  //Prints "The lower bound of key 6 is 4  0"
    return 0; 
}
```
**[Run Code](https://rextester.com/AWN42860)**
