## Pointer
```cpp
int high_score {100};
int low_score  {65};

const int* score_ptr { &high_score };
*score_ptr = 86; // error
score_ptr = &low_score // ok

int* const score_ptr { &high_score };
*score_ptr = 86; // ok
score_ptr = &low_score // error
```

## Object
```cpp
const Player villain {"villain", 100, 55};
```

# int 
```cpp
const int Month = 12;
```