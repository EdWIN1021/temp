---
tags:
  - Function
Belongs to: "[[AActor]]"
Return: 
Description: See if this actor's Tags array contains the supplied name tag
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category="Actor")  
ENGINE_API bool ActorHasTag(FName Tag) const;
```

## Example

```cpp
const FName TargetTag = OwningPawn->ActorHasTag(FName("Player")) ? FName("Enemy"): FName("Player");
```