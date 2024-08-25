```ad-important
Whenever you use new in a constructor to allocate memory, you should use delete in the corresponding destructor to free that memory.
```

```cpp
StringBad::StringBad(const char * s) { 
  str = new char[len + 1]; 
}
```