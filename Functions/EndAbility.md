---
tags:
  - Function
Belongs to: "[[UGameplayAbility]]"
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
virtual void EndAbility(
	const FGameplayAbilitySpecHandle Handle, 
	const FGameplayAbilityActorInfo* ActorInfo,
	const FGameplayAbilityActivationInfo ActivationInfo,              
	bool bReplicateEndAbility,                         
	bool bWasCancelled
);
```

## Example

```cpp
`void UGameplayAbility::EndAbility(
	const FGameplayAbilitySpecHandle Handle,                                          
	const FGameplayAbilityActorInfo* ActorInfo,                                         
	const FGameplayAbilityActivationInfo ActivationInfo,                                     	
	bool bReplicateEndAbility,                                           
	bool bWasCancelled) 
{ 	
	Super::EndAbility(Handle, ActorInfo, ActivationInfo, bReplicateEndAbility, bWasCancelled); 	 	
	if(ActorInfo){     	
		ActorInfo->AbilitySystemComponent->ClearAbility(Handle); 	
	} 
}
```