---
tags:
  - Function
Belongs to: "[[AController]]"
Parameter of: 
Return: 
Interface: 
Description: Get the control rotation
Type:
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category=Pawn) 
ENGINE_API virtual FRotator GetControlRotation() const;
```

## Example

```cpp
const FRotator Rotation = GetControlRotation();
```