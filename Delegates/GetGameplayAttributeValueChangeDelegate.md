---
tags:
  - Delegate
Class:
  - "[[UAbilitySystemComponent]]"
Struct:
  - "[[FOnGameplayAttributeValueChange]]"
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

