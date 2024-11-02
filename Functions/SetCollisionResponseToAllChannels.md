---
tags:
  - Function
Belongs to: "[[UPrimitiveComponent]]"
Parameter of: 
Return: 
Interface: 
Description: 
Type:
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category="Collision") 
ENGINE_API virtual void SetCollisionResponseToAllChannels(ECollisionResponse NewResponse);
```

## Example

```cpp
Sphere->SetCollisionResponseToAllChannels(ECR_Ignore);
```