---
tags:
  - Function
  - Override
Belongs to:
  - "[[UAttributeSet]]"
Parameter of: 
Return: 
Interface: 
Description: Called just before any modification happens to an attribute. This is lower level than PreAttributeModify/PostAttribute modify.There is no additional context provided here since anything can trigger this. Executed effects, duration based effects, effects being removed, immunity being applied, stacking rules changing, etc.This function is meant to enforce things like "Health = Clamp(Health, 0, MaxHealth)" and NOT things like "trigger this extra thing if damage is applied, etc
---

## Declaration

```cpp
virtual void PreAttributeChange(const FGameplayAttribute& Attribute, float& NewValue) { }
```

## Example

```cpp
void UAuraAttributeSet::PreAttributeChange(const FGameplayAttribute& Attribute, float& NewValue)
{
	Super::PreAttributeChange(Attribute, NewValue);
			
	if(Attribute == GetHealthAttribute())
	{
		NewValue = FMath::Clamp(NewValue, 0.f, GetMaxHealth());
	}

	if(Attribute == GetManaAttribute())
	{
		NewValue = FMath::Clamp(NewValue, 0.f, GetMaxMana());
	}
}
```


