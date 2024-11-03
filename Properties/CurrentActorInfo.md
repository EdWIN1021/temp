---
tags:
  - Property
Belongs to: "[[UGameplayAbility]]"
Description: "[[FGameplayAbilityActorInfo]]"
---

## Declaration

```cpp
mutable const FGameplayAbilityActorInfo* CurrentActorInfo;
```

## Example

```cpp
CachedWarriorEnemyCharacter = Cast<AWarriorEnemyCharacter>(CurrentActorInfo->AvatarActor);
```