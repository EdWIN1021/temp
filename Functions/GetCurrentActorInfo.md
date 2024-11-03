---
tags:
  - Function
Belongs to: "[[UGameplayAbility]]"
Return: 
Description: Gets the current actor info bound to this ability - can only be called on instanced abilities.
---

## Declaration

```cpp
const FGameplayAbilityActorInfo* GetCurrentActorInfo() const;
```

## Example

```cpp
APlayerController* PC = Ability->GetCurrentActorInfo()->PlayerController.Get();
```