```cpp
int scores[] { 100, 95, 89 };

// int* scores_ptr = &scores[0];
int* scores_ptr { scores }; 

// subscript notion
scores[0]; // 100
scores_ptr[0]; //100

// offset notion
*scores; // 100
*(scores + 1) // 95

*scores_ptr; //100
*(scores_ptr + 1) // 95
```