---
tags:
  - Function
Belongs to: "[[FGameplayTag]]"
Parameter of: 
Return: 
Interface: 
Description: Gets the FGameplayTag that corresponds to the TagName
---

## Declaration

```cpp
static GAMEPLAYTAGS_API FGameplayTag RequestGameplayTag(const FName& TagName, bool ErrorIfNotFound=true);
```

## Example

```cpp
FGameplayTag MessageTag = FGameplayTag::RequestGameplayTag(FName("Message"));
```