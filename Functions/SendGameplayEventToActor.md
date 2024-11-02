---
tags:
  - Function
Belongs to: "[[UAbilitySystemBlueprintLibrary]]"
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
UFUNCTION(
	BlueprintCallable, 
	Category = Ability, 
	Meta = (
	Tooltip = "This function can be used to trigger an ability on the actor in question with useful payload data.")
) 
static void SendGameplayEventToActor(AActor* Actor, FGameplayTag EventTag, FGameplayEventData Payload);   `
```

## Example

```cpp
```