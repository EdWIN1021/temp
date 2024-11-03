---
tags:
  - Function
Belongs to: "[[UAbilityTask]]"
Return: 
Description: Helper function for instantiating and initializing a new task
---

## Declaration

```cpp
template <class T>
static T* NewAbilityTask(UGameplayAbility* ThisAbility, FName InstanceName = FName())
{
	check(ThisAbility);

	T* MyObj = NewObject<T>();
	MyObj->InitTask(*ThisAbility, ThisAbility->GetGameplayTaskDefaultPriority());

	UAbilityTask::DebugRecordAbilityTaskCreatedByAbility(ThisAbility);

	MyObj->InstanceName = InstanceName;
	return MyObj;
}
```

## Example

```cpp
UTargetDataUnderMouse* UTargetDataUnderMouse::CreateTargetDataUnderMouse(UGameplayAbility* OwningAbility)
{
	UTargetDataUnderMouse* MyObj = NewAbilityTask<UTargetDataUnderMouse>(OwningAbility);
	return MyObj;
}
```