---
tags:
  - Function
Belongs to: 
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
virtual void InitAbilityActorInfo(AActor* InOwnerActor, AActor* InAvatarActor)；
```

## Example

### Owner Actor is a Character

```cpp
// beginplay
AbilitySystemComponent->InitAbilityActorInfo(this, this);
```
