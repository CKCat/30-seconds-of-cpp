# crbegin

**Description** : The function returns an const_reverse_iterator pointing to the last element in the container (i.e., its reverse beginning). The iterator points to past-the-end element of the vector.

**说明：** 该函数返回一个const_reverse_iterator，指向容器中的最后一个元素（即其反向开始）。迭代器指向矢量的末尾元素。

**Example**:
```cpp
// Demonstrates cbegin() 
#include <iostream>
#include <vector>

int main ()
{
  std::vector<int> myvector = {1,2,3,4,5};

  std::cout << "myvector backwards:";
  for (auto rit = myvector.crbegin(); rit != myvector.crend(); ++rit)
    std::cout << ' ' << *rit;
  std::cout << '\n';

  return 0;
}
```
**[Run Code](https://rextester.com/HOY41620)**

