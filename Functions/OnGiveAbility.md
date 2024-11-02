---
tags:
  - Function
Belongs to: 
Parameter of: 
Return: 
Interface: 
Description: Called when the ability is given to an AbilitySystemComponent
---

## Declaration

```cpp
virtual void OnGiveAbility(const FGameplayAbilityActorInfo* ActorInfo, const FGameplayAbilitySpec& Spec);
```

## Example

```cpp
virtual void EndAbility(const FGameplayAbilitySpecHandle Handle, const FGameplayAbilityActorInfo* ActorInfo, const FGameplayAbilityActivationInfo ActivationInfo, bool bReplicateEndAbility, bool bWasCancelled);
```
