# crend

**Description** : The function returns an reverse_iterator pointing to the last element in the container (i.e., its reverse beginning). The iterator points to past-the-end element of the vector. If the container is empty, this function returns the same as vector::cbegin.

该函数返回一个 reverse_iterator 指向容器中的最后一个元素（即它的反向开始）。迭代器指向向量的末尾元素。如果容器为空，则此函数返回与vector::cbegin 相同的值。

**Example**:
```cpp
// Demonstrates cend() 
#include <iostream>
#include <vector>

nt main ()
{
  std::vector<int> myvector = {10,20,30,40,50};

  std::cout << "myvector contains:";

  for (auto it = myvector.crbegin(); it != myvector.crend(); ++it)
    std::cout << ' ' << *it;
  std::cout << '\n';

  return 0;
}
```
**[Run Code](https://rextester.com/HOY41620)**

