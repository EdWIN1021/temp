---
tags:
  - Function
Belongs to: "[[UAbilityTask]]"
Return: 
Description: This should be called prior to broadcasting delegates back into the ability graph. This makes sure the ability is still active.
---

## Declaration

```cpp
bool ShouldBroadcastAbilityTaskDelegates() const;
```

## Example

```cpp
if(ShouldBroadcastAbilityTaskDelegates()){
  ValidData.Broadcast(DataHandle);
}
```