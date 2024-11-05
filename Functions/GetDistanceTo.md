---
tags:
  - Function
Belongs to: "[[AActor]]"
Return: 
Description: Returns the distance from this Actor to OtherActor.
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category = "Transformation")  
ENGINE_API float GetDistanceTo(const AActor* OtherActor) const;
```

## Example

```cpp
const float Distance = OwningPawn->GetDistanceTo(Actor);
```