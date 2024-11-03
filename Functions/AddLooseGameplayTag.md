---
tags:
  - Function
Belongs to: "[[UAbilitySystemComponent]]"
Return: 
Description: Allows GameCode to add loose gameplaytags which are not backed by a GameplayEffect.​Tags added this way are not replicated! Use the 'Replicated' versions of these functions if replication is needed.​It is up to the calling GameCode to make sure these tags are added on clients/server where necessary
---

## Declaration

```cpp
FORCEINLINE void AddLooseGameplayTag(const FGameplayTag& GameplayTag, int32 Count=1)
{
  UpdateTagMap(GameplayTag, Count);
}
```

## Example

```cpp
ASC->AddLooseGameplayTag(TagToAdd);
```