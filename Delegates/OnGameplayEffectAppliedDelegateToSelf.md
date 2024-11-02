---
tags:
  - Delegate
Belongs to:
  - "[[UAbilitySystemComponent]]"
Description: Called on server whenever a GE is applied to self. This includes instant and duration based GEs.
---

## Declaration

```cpp
FOnGameplayEffectAppliedDelegate OnGameplayEffectAppliedDelegateToSelf
  MulticastDelegate: (
	  UAbilitySystemComponent*, 
	  const FGameplayEffectSpec&, 
	  FActiveGameplayEffectHandle) -> void
```

## Example

```cpp
OnGameplayEffectAppliedDelegateToSelf.AddUObject(this, &U<Project>AbilitySystemComponent::<Function>);
```

