---
tags:
  - Function
Belongs to: "[[AController]]"
Return: 
Interface: 
Description: Replication Notification Callbacks
---

## Declaration

```cpp
UFUNCTION()
ENGINE_API virtual void OnRep_PlayerState();
```

## Example

```cpp
void AAuraCharacter::OnRep_PlayerState()
{
	Super::OnRep_PlayerState();
	
	// Init ability actor info for the client
	InitAbilityActorInfo();
}
```