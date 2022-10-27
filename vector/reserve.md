# reserve

**Description** :
- Helps specify the minimum size of a vector
- Useful to know how many elements the vector will ultimately hold

**描述 ：**
- 帮助指定向量的最小大小。
- 有助于了解向量最终将包含多少个元素。

**Example**:
```cpp
	//create an empty vector
        std::vector<int> myvector;

        //reserve a size of 'atleast' 5 elements
        myvector.reserve(5);

        //inserting 5 elements
        for(int i=0; i<5; i++)
        {
                myvector.push_back(i);
        }
```

**[See sample code](..snippets/vector/reserve.cpp)**
**[Run Code](https://rextester.com/AMLWGW9232)**

