---
tags:
  - Function
Belongs to: 
Parameter of: 
Return: 
Interface: 
Description: 
Type:
---

## Declaration

```cpp
UFUNCTION(
  BlueprintCallable, 
  Category="Components|SkeletalMesh",
  meta=(Keywords = "AnimBlueprint", UnsafeDuringActorConstruction = "true")
)
ENGINE_API class UAnimInstance * GetAnimInstance() const;
```

## Example

```cpp
GetMesh()->GetAnimInstance()
```
