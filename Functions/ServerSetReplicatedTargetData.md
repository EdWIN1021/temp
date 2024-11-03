---
tags:
  - Function
Belongs to: "[[UAbilitySystemComponent]]"
Return: 
Description: Replicates targeting data to the server
---

## Declaration

```cpp
UFUNCTION(Server, reliable, WithValidation)
void ServerSetReplicatedTargetData(
  FGameplayAbilitySpecHandle AbilityHandle, 
  FPredictionKey AbilityOriginalPredictionKey, 
  const FGameplayAbilityTargetDataHandle& ReplicatedTargetDataHandle, 
  FGameplayTag ApplicationTag, FPredictionKey CurrentPredictionKey);
```

## Example

```cpp
AbilitySystemComponent->ServerSetReplicatedTargetData(
  GetAbilitySpecHandle(),
  GetActivationPredictionKey(),
  DataHandle,
  FGameplayTag(), // An empty tag is being passed
  AbilitySystemComponent->ScopedPredictionKey);
```