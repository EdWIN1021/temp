---
tags:
  - Macro
Description: GAMEPLAYATTRIBUTE_REPNOTIFY macro handles  (like UI or gameplay logic) that the attribute has changed, allowing for appropriate updates.
Belongs to:
---

## Declaration

```cpp
#define GAMEPLAYATTRIBUTE_REPNOTIFY(ClassName, PropertyName, OldValue) \
{ \
	static FProperty* ThisProperty = FindFieldChecked<FProperty>(ClassName::StaticClass(), GET_MEMBER_NAME_CHECKED(ClassName, PropertyName)); \
	GetOwningAbilitySystemComponentChecked()->SetBaseAttributeValueFromReplication(FGameplayAttribute(ThisProperty), PropertyName, OldValue); \
}
```

## Example

```cpp
void <Project>AttributeSet::OnRep_<Attribute>(const FGameplayAttributeData& Old<Attribute>) const
{
  GAMEPLAYATTRIBUTE_REPNOTIFY(<Project>AttributeSet, Attribute, Old<Attribute>);
}
```

## Options
- 