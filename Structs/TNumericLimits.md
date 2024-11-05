---
tags:
  - Struct
Belongs to: 
Description:
---

## Declaration

```cpp
template<>  
struct TNumericLimits<float> {  
    typedef float NumericType;  
  
    static constexpr NumericType Min()  
    {       return MIN_flt;  
    }  
    static constexpr NumericType Max()  
    {       return MAX_flt;  
    }  
    static constexpr NumericType Lowest()  
    {       return -Max();  
    }};

```

## Example

```cpp
float ClosestDistance = TNumericLimits<float>::Max();
```
