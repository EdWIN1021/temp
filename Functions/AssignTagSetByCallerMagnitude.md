---
tags:
  - Function
Belongs to: "[[UAbilitySystemBlueprintLibrary]]"
Return: 
Description: Sets a gameplay tag Set By Caller magnitude value
---

## Declaration

```cpp
// Gameplay Ability: Set by Caller
UFUNCTION(BlueprintCallable, Category = "Ability|GameplayEffect", meta = (GameplayTagFilter = "SetByCaller"))
static FGameplayEffectSpecHandle AssignTagSetByCallerMagnitude(
  FGameplayEffectSpecHandle SpecHandle,
  FGameplayTag DataTag, 
  float Magnitude
);
```

## Example

```cpp
UAbilitySystemBlueprintLibrary::AssignTagSetByCallerMagnitude(SpecHandle,GameplayTags.Damage, 50.f);
```