---
tags:
  - Function
Belongs to: "[[UAbilitySystemComponent]]"
Parameter of: 
Return: "[[FGameplayEffectContextHandle]]"
Interface: 
Description: Create an EffectContext for the owner of this AbilitySystemComponent
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category = GameplayEffects)
virtual FGameplayEffectContextHandle MakeEffectContext() const;
```

## Example

```cpp
FGameplayEffectContextHandle PrimaryAttributesContextHandle = ASC->MakeEffectContext();
```