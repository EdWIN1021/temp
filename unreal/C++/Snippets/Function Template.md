```cpp
template<typename T>
inline T AItem::Avg(T First, T Second){
  return (First + Second) / 2;
}

Avg<int32>(1, 3);
```