# rbegin

**Description** : 
- Returns a reverse iterator pointing to the last element in the vector (i.e., its reverse beginning).
- Reverse iterators iterate backwards: increasing them moves them towards the beginning of the container.

**描述 ：**
- 返回一个反向迭代器，指向向量中的最后一个元素（即它的反向开始）。
- 反向迭代器向后迭代：增加它们会将它们移向容器的开头。

**Example**:
```cpp
	// Iterate backwards over myVector using reverse iterators
	for (auto it = myVector.rbegin(); it != myVector.rend(); it++) {
		std::cout << *it << " ";
	}
```
**[See Sample code](../snippets/vector/rbegin.cpp)**
**[Run Code](https://rextester.com/XGWC54800)**
