```ad-important
It is an object that acts as a pointer to elements within a container (like a vector, list, or map).
```



```cpp
std::vector<int>::iterator it1;
std::list<std::string>::iterator it2;
std::map<std::string, std::string>::iterator it3;
std::set<char>::iterator it4;
```

```cpp
std:vector<int> vec {1,2,3};

std:vector<int>::iterator it = vec.begin();
auto it = vec.begin();

while(it != vec.end()){
  std::count << *it << " ";
  ++it;
}
```