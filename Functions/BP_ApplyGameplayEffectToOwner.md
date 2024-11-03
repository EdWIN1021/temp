---
tags:
  - Function
Belongs to: 
Return: 
Description:
---

## Declaration

```cpp
UFUNCTION(
  BlueprintCallable, 
  Category = Ability, DisplayName="ApplyGameplayEffectToOwner",
  meta=(ScriptName="ApplyGameplayEffectToOwner")
)
FActiveGameplayEffectHandle BP_ApplyGameplayEffectToOwner(
  TSubclassOf<UGameplayEffect> GameplayEffectClass, 
  int32 GameplayEffectLevel = 1, 
  int32 Stacks = 1
);

```

## Example

```cpp
```