---
tags:
  - Function
Belongs to:
  - "[[UAbilitySystemComponent]]"
Struct: 
Description:
---

## Declaration

```cpp
FOnGameplayAttributeValueChange& GetGameplayAttributeValueChangeDelegate(FGameplayAttribute Attribute);
```

## Example

```cpp
AbilitySystemComponent->GetGameplayAttributeValueChangeDelegate(  
    <Attribute>).AddUObject(this, &<Class>::<Attribute>Changed);
```

