- ! The body of a range for must not change the size of the sequence over which it is iterating

```cpp
string s{ "some string" };

for(auto c : s) {
  cout << c << endl;
}
```