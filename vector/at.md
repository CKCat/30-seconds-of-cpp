# at

**Description** : 
- Returns a reference to the element at position _n_ in the vector.

- If the position is not present in the vector, it throws exception of type _out_of_range_ 

**描述 ：**
- 返回对向量中位置 n 处元素的引用。
- 如果向量中不存在该位置，则抛出 out_of_range 类型的异常。

**Example**:
```cpp
	// Create a vector of 5 integers  
	std::vector<int> myVector{1, 2, 3, 4, 5};

	// Display the contents of vector using std::vector::at.
	for (int i = 0; i < 5; i++) {
	    std::cout << myVector.at(i) << " ";
	}
```
**[See Sample code](../snippets/vector/at.cpp)**
**[Run Code](https://rextester.com/ZGMP1944)**
