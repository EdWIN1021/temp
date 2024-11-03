---
tags:
  - Function
Belongs to: "[[FGameplayEffectCustomExecutionParameters]]"
Return: 
Interface: 
Description: Simple accessor to source ability system component (could be null!)
---

## Declaration

```cpp
UAbilitySystemComponent* GetSourceAbilitySystemComponent() const;
```

## Example

```cpp
const UAbilitySystemComponent* SourceASC = ExecutionParams.GetSourceAbilitySystemComponent();
```