---
tags:
  - Class
Derived from: "[[UObject]]"
Parameter of:
  - "[[ATTRIBUTE_ACCESSORS]]"
  - "[[DOREPLIFETIME_CONDITION_NOTIFY]]"
Description:
---

## Declaration
```cpp
UPROPERTY() 
TObjectPtr<UAttributeSet> AttributeSet;
```

## Example
```cpp
AttributeSet = CreateDefaultSubobject<UAuraAttributeSet>("AttributeSet");
```