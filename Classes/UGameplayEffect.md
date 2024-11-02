---
tags:
  - Class
Derived from: "[[UObject]]"
Initialization: 
Declaration: 
Description:
---

## Declaration

```cpp
UPROPERTY(EditDefaultsOnly, Category="Class Defaults")
TSubclassOf<UGameplayEffect> PrimaryAttributes;
```

## Example

```cpp

```

## Blueprint
- Calculation Class -> UGameplayEffectExecutionCalculation
- Attribute Based Magnitude -> C * ( 9 + Pre ) + Post