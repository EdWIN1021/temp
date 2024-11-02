---
tags:
  - Function
Derived from: "[[UActorComponent]]"
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
FActiveGameplayEffectHandle ApplyGameplayEffectToSelf(
  const UGameplayEffect *GameplayEffect,  	
  float Level,  	
  const FGameplayEffectContextHandle& EffectContext,  	
  FPredictionKey PredictionKey = FPredictionKey() 
);
```

## Example

```cpp
InASCToGive->ApplyGameplayEffectToSelf(EffectCDO, ApplyLevel, InASCToGive->MakeEffectContext());
```

## Options
- 