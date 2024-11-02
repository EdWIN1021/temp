---
tags:
  - Function
Belongs to: "[[FGameplayTag]]"
Parameter of: 
Return: 
Interface: 
Description: Determine if TagToCheck is valid and exactly matches this tag
---

## Declaration

```cpp
FORCEINLINE bool MatchesTagExact(const FGameplayTag& TagToCheck) const { 
	if (!TagToCheck.IsValid()) { 
		return false; 
	} 
	// Only check check explicit tag list return 
	TagName == TagToCheck.TagName; 
}
```

## Example

```cpp
Info.AttributeTag.MatchesTagExact(AttributeTag)
```