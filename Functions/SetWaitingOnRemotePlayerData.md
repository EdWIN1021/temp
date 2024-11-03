---
tags:
  - Function
Belongs to: "[[UAbilityTask]]"
Return: 
Description: Called when the ability task is waiting on remote player data. IF the remote player ends the ability prematurely, and a task with this set is still running, the ability is killed
---

## Declaration

```cpp
void SetWaitingOnRemotePlayerData();
```

## Example

```cpp
if(!bCalledDelegate)
{
  SetWaitingOnRemotePlayerData();
}
```