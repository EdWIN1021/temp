---
tags:
  - Function
Belongs to: "[[UAbilitySystemComponent]]"
Parameter of: 
Return: 
Interface: 
Description: Check if the asset has a gameplay tag that matches against the specified tag expands to include parents of asset tags
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category=GameplayTags) GAMEPLAYTAGS_API virtual bool HasMatchingGameplayTag(FGameplayTag TagToCheck) const;
```

## Example

```cpp
ASC->HasMatchingGameplayTag(TagToAdd);
```