---
tags:
  - Function
Belongs to: "[[UPrimitiveComponent]]"
Parameter of: 
Return: 
Interface: 
Description: Controls what kind of collision is enabled for this body
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category="Collision") 
ENGINE_API virtual void SetCollisionEnabled(ECollisionEnabled::Type NewType);
```

## Example

```cpp
GetMesh()->SetCollisionEnabled(ECollisionEnabled::PhysicsOnly);
GetCapsuleComponent()->SetCollisionEnabled(ECollisionEnabled::NoCollision);
```