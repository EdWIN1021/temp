---
tags:
  - Function
Belongs to: "[[UAnimInstance]]"
Parameter of: 
Return: 
Interface: 
Description: Makes a montage jump to a named section. If Montage reference is NULL, it will do that to all active montages.
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category="Animation|Montage")
ENGINE_API void Montage_JumpToSection(
  FName SectionName, 
  const UAnimMontage* Montage = NULL
);
```

## Example

```cpp
```
