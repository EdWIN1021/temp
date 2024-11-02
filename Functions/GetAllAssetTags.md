---
tags:
  - Function
Belongs to: "[[FGameplayEffectSpec]]"
Parameter of: 
Return: 
Interface: 
Description: Appends all tags that apply to this gameplay effect spec
Struct:
---

## Declaration

```cpp
void GetAllAssetTags(OUT FGameplayTagContainer& OutContainer) const;
```

## Example

```cpp
FGameplayTagContainer TagContainer;   
EffectSpec.GetAllAssetTags(TagContainer);
```

## Options
- 