---
tags:
  - Function
Belongs to: "[[UAbilitySystemComponent]]"
Parameter of: 
Return: "[[FGameplayEffectSpecHandle]]"
Interface: 
Description: Get an outgoing GameplayEffectSpec that is ready to be applied to other things.
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category = GameplayEffects)
virtual FGameplayEffectSpecHandle MakeOutgoingSpec(
  TSubclassOf<UGameplayEffect> GameplayEffectClass, 
  float Level, 
  FGameplayEffectContextHandle Context
) const;
```

## Example

```cpp
const FGameplayEffectSpecHandle EffectSpecHandle = TargetASC->MakeOutgoingSpec(
  // GE blueprint
  GameplayEffectClass, 
  ActorLevel, 
  EffectContextHandle
);
```