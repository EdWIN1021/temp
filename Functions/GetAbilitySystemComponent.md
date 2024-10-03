---
tags:
  - Function
Class: "[[UAbilitySystemBlueprintLibrary]]"
Parameters: 
Return: 
Interface: "[[IAbilitySystemInterface]]"
Description: 
Type:
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

## Getter

```cpp
```

## Options
- [[MakeEffectContext]]
- [[MakeOutgoingSpec]]
- [[ApplyGameplayEffectSpecToSelf]]