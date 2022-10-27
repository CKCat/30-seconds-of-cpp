# rend

**Description** : 
- Returns a reverse iterator pointing to the theoretical element preceding the first element in the vector (which is considered its reverse end).
- Reverse iterators iterate backwards: increasing them moves them towards the beginning of the container.

**描述**
- 返回指向向量中第一个元素之前的理论元素的反向迭代器（这被认为是它的反向端）。
- 反向迭代器向后迭代：增加它们会使它们向容器的开头移动。

**Example**:
```cpp
	// Iterate backwards over myVector using reverse iterators
	for (auto it = myVector.rbegin(); it != myVector.rend(); it++) {
		std::cout << *it << " ";
	}
```
**[See Sample code](../snippets/vector/rend.cpp)**
**[Run Code](https://rextester.com/XGWC54800)**
