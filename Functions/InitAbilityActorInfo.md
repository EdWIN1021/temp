---
tags:
  - Function
Class: 
Parameters: 
Return: 
Interface: 
Description: 
Initialization:
  - "[[BeginPlay]]"
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
### Owner Actor is a PlayerState
- Client: [[OnRep_PlayerState]]
- Server: [[PossessedBy]]
