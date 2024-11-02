---
tags:
  - Function
Belongs to:
  - "[[UAbilitySystemBlueprintLibrary]]"
Parameter of: 
Return: 
Interface: "[[IAbilitySystemInterface]]"
Description:
---

## Declaration

```cpp
virtual UAbilitySystemComponent* GetAbilitySystemComponent() const override;

static UAbilitySystemComponent* GetAbilitySystemComponent(AActor* Actor);
```

## Example

```cpp
UAbilitySystemComponent* <Character>/<PlayerState>::GetAbilitySystemComponent() const { 
	return AbilitySystemComponent; 
}

AbilitySystemComponent* TargetASC = UAbilitySystemBlueprintLibrary::GetAbilitySystemComponent(Target);
```
