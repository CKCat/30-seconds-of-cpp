# emplace

**Description** : The emplace() member inserts an element at the top
of the stack and constructs the element in place from the arguments
provided. This can be more efficient than push in certain situations
and avoid temporaries. emplace() effectively forwards its arguments to
a constructor that is placed at the top of the stack.

说明： emplace() 成员在堆栈顶部插入一个元素，并根据提供的参数在适当位置构造该元素。这可能比在某些情况下推送更有效并避免临时性。 emplace() 有效地将其参数转发给放置在堆栈顶部的构造函数。

**Example**:
```cpp
    std::stack<std::string> st;
    // Add some strings to the stack
    st.emplace("C++ world");
    st.emplace("Hello");
    std::cout << st.top();
    st.pop();
    std::cout << ", " << st.top() << std::endl;
```
**[Run Code](https://rextester.com/TJAOH56215)**
