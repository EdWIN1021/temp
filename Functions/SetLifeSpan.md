---
tags:
  - Function/Blueprint
Belongs to: "[[AActor]]"
Description: Set the lifespan of this actor. When it expires the object will be destroyed. If requested lifespan is 0, the timer is cleared and the actor will not be destroyed.
---
## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category="Actor", meta=(Keywords = "delete destroy"))
ENGINE_API virtual void SetLifeSpan( float InLifespan );
```

## Example

```cpp
SetLifeSpan(LifeSpan);
```