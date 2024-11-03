---
tags:
  - Function
Belongs to: "[[UAbilitySystemComponent]]"
Parameter of:
  - "[[FGameplayEffectSpecHandle]]"
Return: 
Interface: 
Description: This applies the effect specification to the target actor
---

## Declaration

```cpp
virtual FActiveGameplayEffectHandle ApplyGameplayEffectSpecToSelf(
  const FGameplayEffectSpec& GameplayEffect, 
  FPredictionKey PredictionKey = FPredictionKey()
);
```

## Example

```cpp
TargetASC->ApplyGameplayEffectSpecToSelf(*DamageEffectSpecHandle.Data.Get());
```
