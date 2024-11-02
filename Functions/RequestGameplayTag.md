---
tags:
  - Function
Belongs to: 
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
static GAMEPLAYTAGS_API FGameplayTag RequestGameplayTag(const FName& TagName, bool ErrorIfNotFound=true);
```

## Example

```cpp
FGameplayTag MessageTag = FGameplayTag::RequestGameplayTag(FName("Message"))
```

## Options
- 