- function will be called on clients when the property changes on the server
- [[GAMEPLAYATTRIBUTE_REPNOTIFY]]

```cpp
UFUNCTION()  
void OnRep_<Attribute>(const FGameplayAttributeData& <OldAttribute>) const;

void <Project>AttributeSet::OnRep_<Attribute>(const FGameplayAttributeData& Old<Attribute>) const  
{  
  GAMEPLAYATTRIBUTE_REPNOTIFY(<Project>AttributeSet, Attribute, Old<Attribute>);  
}
```
