---
tags:
  - Function
Belongs to: 
Return: 
Description: This boolean helps determine whether the ability is being executed by the local player (on the client) or by another client/server.
---

## Declaration

```cpp
bool IsLocallyControlled() const;
```

## Example

```cpp
const bool bIsLocallyControlled = Ability->GetCurrentActorInfo()->IsLocallyControlled();
```