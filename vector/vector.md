# Vector

**Description :** Vectors are sequence containers representing arrays that can change in size, they are a generic templete and will use whatever generic type you assign to it. Vectors are similar to arrays in that 
they hold data in cells, these cells are dynamically allocated and deallocated automatically. Below are 4 constructor examples of how to create vector objects.

**描述 :** 向量是表示可以改变大小的数组的序列容器，它们是通用模板，并且将使用您分配给它的任何通用类型。向量类似于数组，因为它们将数据保存在单元格中，这些单元格是动态分配和自动释放的。下面是如何创建矢量对象的 4 个构造函数示例。

**Example** :

```cpp
#include <iostream>
#include <vector>

int main(void)
{
	std::vector<int> emptyConstructor;														// Creates an empty vector
	std::vector<int> fillConstructor(5, 10);												// Fills the vector with 5 values of 10
	std::vector<int> iteratedConstructor(fillConstructor.begin(), fillConstructor.end()-2);   // Fills the vector with the iterated object values from beginning to end
	std::vector<int> copiedConstructor(iteratedConstructor);								// Creates a duplicate of the 

	// emptyConstructor {}
	// fillConstructor {10, 10, 10, 10, 10}
	// iteratedConstructor {10, 10, 10}
	// copiedConstructor {10, 10, 10}

	system("pause");
	return 0;
}
```
**[Run Code](https://rextester.com/ATPSZ75822)**
