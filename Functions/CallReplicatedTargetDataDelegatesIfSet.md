---
tags:
  - Function
Belongs to: "[[UAbilitySystemComponent]]"
Return: 
Description: Calls the TargetData Confirm/Cancel events if they have been sent.
---

## Declaration

```cpp
bool CallReplicatedTargetDataDelegatesIfSet(
  FGameplayAbilitySpecHandle AbilityHandle, 
  FPredictionKey AbilityOriginalPredictionKey
);
```

## Example

```cpp
const bool bCalledDelegate = AbilitySystemComponent.Get()->CallReplicatedTargetDataDelegatesIfSet(
  SpecHandle, 
  ActivationPredictionKey
);
```