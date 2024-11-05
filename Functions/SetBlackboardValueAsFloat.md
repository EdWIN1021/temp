---
tags:
  - Function
Belongs to: "[[UBTFunctionLibrary]]"
Return: 
Description:
---

## Declaration

```cpp
UFUNCTION(BlueprintPure, Category="AI|BehaviorTree", Meta=(HidePin="NodeOwner", DefaultToSelf="NodeOwner"))  
static AIMODULE_API float GetBlackboardValueAsFloat(UBTNode* NodeOwner, const FBlackboardKeySelector& Key);
```

## Example

```cpp
UBTFunctionLibrary::SetBlackboardValueAsFloat(this, DistanceToTargetSelector, ClosestDistance);
```