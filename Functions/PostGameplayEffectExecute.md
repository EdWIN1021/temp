---
tags:
  - Function
  - Override
Belongs to: "[[UAttributeSet]]"
Return: 
Interface: 
Description: Called just after a GameplayEffect is executed to modify the base value of an attribute. No more changes can be made.​Note this is only called during an 'execute'. E.g., a modification to the 'base value' of an attribute. It is not called during an application of a GameplayEffect, such as a 5 second +10 movement speed buff.
Type:
---

## Declaration

```cpp
virtual void PostGameplayEffectExecute(const struct FGameplayEffectModCallbackData &Data) { }
```

## Example

```cpp
void UAuraAttributeSet::PostGameplayEffectExecute(const FGameplayEffectModCallbackData& Data)
{
	Super::PostGameplayEffectExecute(Data);
	if(Data.EvaluatedData.Attribute == GetManaAttribute())
	{
		SetMana(FMath::Clamp(GetMana(), 0.f, GetMaxMana()));
	}
}
```