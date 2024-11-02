---
tags:
  - Function
Belongs to: "[[USceneComponent]]"
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category="Transformation", meta=(Keywords="Bone")) ENGINE_API virtual FVector GetSocketLocation(FName InSocketName) const;
```

## Example

```cpp
Weapon->GetSocketLocation(WeaponTipSocketName)
```