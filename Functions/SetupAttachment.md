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
ENGINE_API void SetupAttachment(USceneComponent* InParent, FName InSocketName = NAME_None);
```

## Example

```cpp
HealthBar->SetupAttachment(GetRootComponent());
```