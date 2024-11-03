---
tags:
  - Struct
Belongs to: 
Description: Its purpose is to ensure that certain actions taken by the client (such as ability activation or gameplay events) are predicted locally and synchronized correctly with the server.
---

## Declaration

```cpp
FScopedPredictionWindow(UAbilitySystemComponent* AbilitySystemComponent, FPredictionKey InPredictionKey, bool InSetReplicatedPredictionKey = true);
```

## Example

```cpp
FScopedPredictionWindow ScopedPredictionWindow(AbilitySystemComponent.Get());
```
