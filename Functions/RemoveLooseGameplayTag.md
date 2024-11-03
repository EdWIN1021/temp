---
tags:
  - Function
Belongs to: "[[UAbilitySystemComponent]]"
Return: 
Description:
---

## Declaration

```cpp
FORCEINLINE void RemoveLooseGameplayTag(const FGameplayTag& GameplayTag, int32 Count = 1)
{
	UpdateTagMap(GameplayTag, -Count);
}
```

## Example

```cpp
ASC->RemoveLooseGameplayTag(TagToRemove);
```