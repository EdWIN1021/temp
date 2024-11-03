---
tags:
  - Function
Belongs to: "[[UAbilitySystemComponent]]"
Return: 
Description: Consumes cached TargetData from client (only TargetData)
---

## Declaration

```cpp
void ConsumeClientReplicatedTargetData(
  FGameplayAbilitySpecHandle AbilityHandle, 
  FPredictionKey AbilityOriginalPredictionKey
);
```

## Example

```cpp
AbilitySystemComponent->ConsumeClientReplicatedTargetData(GetAbilitySpecHandle(), GetActivationPredictionKey());
```