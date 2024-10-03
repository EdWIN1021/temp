---
tags:
  - Class
Base: 
Initialization: "[[Constructor]]"
Has: 
Declaration:
  - "[[ACharacter]]"
  - "[[APlayerState]]"
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

## Options
- [[FGameplayAttributeData | Create Attribute]]