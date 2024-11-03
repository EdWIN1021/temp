---
tags:
  - Function
Belongs to: "[[UGameplayAbility]]"
Parameter of: 
Return: 
Interface: 
Description: Called when the ability is given to an AbilitySystemComponent
---

## Declaration

```cpp
virtual void OnGiveAbility(const FGameplayAbilityActorInfo* ActorInfo, const FGameplayAbilitySpec& Spec);
```

## Example

```cpp
void UWarriorGameplayAbility::OnGiveAbility(
	const FGameplayAbilityActorInfo* ActorInfo,
	const FGameplayAbilitySpec& Spec) { 	
		Super::OnGiveAbility(ActorInfo, Spec); 	 	
		
		if(ActorInfo && !Spec.IsActive()) { 
			ActorInfo->AbilitySystemComponent->TryActivateAbility(Spec.Handle); 
		} 
}
```
