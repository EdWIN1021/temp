---
tags:
  - Function
  - Override
Belongs to:
  - "[[UAttributeSet]]"
Parameter of: 
Return: 
Interface: 
Description: Called just before any modification happens to an attribute.
---

## Declaration

```cpp
virtual void PreAttributeChange(const FGameplayAttribute& Attribute, float& NewValue) {}
```

## Example

```cpp
void UAttributeSet::PreAttributeChange(const FGameplayAttribute& Attribute, float& NewValue) { }
```


