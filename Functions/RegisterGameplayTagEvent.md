---
tags:
  - Function
Belongs to: "[[UAbilitySystemComponent]]"
Return: 
Description: Allow events to be registered for specific gameplay tags being added or removed
---

## Declaration

```cpp
FOnGameplayEffectTagCountChanged& RegisterGameplayTagEvent(
  FGameplayTag Tag, 
  EGameplayTagEventType::Type EventType=EGameplayTagEventType::NewOrRemoved
);
```

## Example

```cpp
AbilitySystemComponent->RegisterGameplayTagEvent(
  FAuraGameplayTags::Get().Effects_HitReact, 
  EGameplayTagEventType::NewOrRemoved
  )
  .AddUObject(
    this,
	&AAuraEnemy::HitReactTagChanged
  );
```