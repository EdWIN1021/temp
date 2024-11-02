---
tags:
  - Class
Belongs to: "[[UObject]]"
Initialization: 
Has: 
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

## Getter
```cpp
UAttributeSet* GetAttributeSet() const { return AttributeSet; };
```