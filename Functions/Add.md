---
tags:
  - Function
Belongs to: "[[FGameplayAbilityTargetDataHandle]]"
Return: 
Description:
---

## Declaration

```cpp
void Add(FGameplayAbilityTargetData* DataPtr)
{
  Data.Add(TSharedPtr<FGameplayAbilityTargetData>(DataPtr));
}
```

## Example

```cpp
DataHandle.Add(Data);
```