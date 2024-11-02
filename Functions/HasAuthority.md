---
tags:
  - Function
Belongs to: "[[UGameplayAbility]]"
Parameter of: 
Return: 
Interface: 
Description: True if this is the server or single player
---

## Declaration

```cpp
bool HasAuthority(const FGameplayAbilityActivationInfo* ActivationInfo) const;
```

## Example

```cpp
const bool bIsServer = HasAuthority(&ActivationInfo);
```