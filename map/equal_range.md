# equal_range
**Description :** Returns the bounds of a range that includes all the elements in the container which have a key equivalent to k.

说明：返回一个范围的边界，该范围包括容器中所有具有与 k 等效的键的元素。

**Example** :

```cpp
// Demonstrates equal_range

#include <iostream>
#include <map>

int main (){
	std::map<char,int> mymap;

  	mymap['a']=10;
  	mymap['b']=20;
  	mymap['c']=30;

  	std::pair<std::map<char,int>::iterator,std::map<char,int>::iterator> ret;
  	ret = mymap.equal_range('b');

  	std::cout << "lower bound points to: ";
  	std::cout << ret.first->first << " => " << ret.first->second << '\n';

  	std::cout << "upper bound points to: ";
  	std::cout << ret.second->first << " => " << ret.second->second << '\n';

  	return 0;
}

```
**[Run Code](https://rextester.com/PDL21133)**
