---
tags:
  - Function
Belongs to: "[[UAbilitySystemComponent]]"
Parameter of: 
Return: 
Interface: 
Description: Initialized the Abilities' ActorInfo - the structure that holds information about who we are acting on and who controls us.
---

## Declaration

```cpp
/* 
	OwnerActor is the actor that logically owns this component. 
	AvatarActor is what physical actor in the world we are acting on. 
	Usually a Pawn but it could be a Tower, Building, Turret, etc, may be the same as Owner 
*/

virtual void InitAbilityActorInfo(AActor* InOwnerActor, AActor* InAvatarActor)；
```

## Example

```cpp
AbilitySystemComponent->InitAbilityActorInfo(this, this);
```
