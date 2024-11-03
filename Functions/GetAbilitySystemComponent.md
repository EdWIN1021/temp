---
tags:
  - Function
Belongs to:
  - "[[UAbilitySystemBlueprintLibrary]]"
Parameter of: 
Return: 
Description:
---

## Declaration

```cpp
UFUNCTION(BlueprintPure, Category = Ability, Meta=(DefaultToSelf = "Actor"))
static UAbilitySystemComponent* GetAbilitySystemComponent(AActor* Actor);
```

## Example

```cpp
UAbilitySystemComponent* TargetASC = UAbilitySystemBlueprintLibrary::GetAbilitySystemComponent(TargetActor);
```
