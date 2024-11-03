---
tags:
  - Struct
Description: 
Belongs to:
---

## Declaration

```cpp
DECLARE_DYNAMIC_MULTICAST_DELEGATE_OneParam(FOnChaosBreakEvent, const FChaosBreakEvent&, BreakEvent);
```

## Example

```cpp
UPROPERTY(BlueprintAssignable, Category = "Chaos")
FOnChaosBreakEvent OnChaosBreakEvent;
```
