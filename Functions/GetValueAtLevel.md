---
tags:
  - Function
Belongs to: "[[FScalableFloat]]"
Return: 
Description: Returns the scaled value at a given level
---

## Declaration

```cpp
float GetValueAtLevel(float Level, const FString* ContextString = nullptr) const;
```

## Example

```cpp
const float ScaledDamage = Damage.GetValueAtLevel(20);
```