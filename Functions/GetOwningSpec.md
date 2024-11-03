---
tags:
  - Function
Belongs to: "[[FGameplayEffectCustomExecutionParameters]]"
Return: 
Interface: Simple accessor to owning gameplay spec
Description:
---

## Declaration

```cpp
const FGameplayEffectSpec& GetOwningSpec() const;
```

## Example

```cpp
const FGameplayEffectSpec& Spec = ExecutionParams.GetOwningSpec();
```