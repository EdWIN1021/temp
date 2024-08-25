```ad-important
accessing the value stored at the memory address that a pointer is pointing to.
```

```cpp
int score {100};
int* score_ptr {&scrore};

*score_ptr = 200;
```