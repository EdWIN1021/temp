---
tags:
  - Function
Belongs to: "[[FGameplayEffectCustomExecutionParameters]]"
Return: 
Interface: 
Description: Simple accessor to target ability system componen
---

## Declaration

```cpp
UAbilitySystemComponent* GetTargetAbilitySystemComponent() const;
```

## Example

```cpp
const UAbilitySystemComponent* TargetASC = ExecutionParams.GetTargetAbilitySystemComponent();
```