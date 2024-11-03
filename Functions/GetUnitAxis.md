---
tags:
  - Function
Belongs to: "[[TMatrix]]"
Parameter of: 
Return: 
Interface: 
Description: get unit length axis of this matrix
---
## Declaration

```cpp
inline TVector<T> GetUnitAxis(EAxis::Type Axis) const;
```

## Example

```cpp
const FVector ForwardDirection = FRotationMatrix(YawRotation).GetUnitAxis(EAxis::X);
```