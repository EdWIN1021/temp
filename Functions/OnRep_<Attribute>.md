---
tags:
  - Function
Belongs to: "[[FGameplayAttributeData]]"
Parameter of: 
Return: 
Interface: 
Description: function will be called on clients when the property changes on the server
---

## Declaration

```cpp
UFUNCTION()
void <Project>AttributeSet::OnRep_<Attribute>(const FGameplayAttributeData& Old<Attribute>) const
```

## Example

```cpp
void <Project>AttributeSet::OnRep_<Attribute>(const FGameplayAttributeData& Old<Attribute>) const
{
  GAMEPLAYATTRIBUTE_REPNOTIFY(<Project>AttributeSet, Attribute, Old<Attribute>);
}
```

