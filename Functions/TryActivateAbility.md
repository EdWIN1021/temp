---
tags:
  - Function
Belongs to: "[[UAbilitySystemComponent]]"
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category = "Abilities") 
bool TryActivateAbility(
	FGameplayAbilitySpecHandle AbilityToActivate, 
	bool bAllowRemoteActivation = true
);
```

## Example

```cpp
TryActivateAbility(AbilitySpec.Handle);
```