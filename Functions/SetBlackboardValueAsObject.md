---
tags:
  - Function
Belongs to: "[[UBTFunctionLibrary]]"
Return: 
Description:
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category="AI|BehaviorTree", Meta=(HidePin="NodeOwner", DefaultToSelf="NodeOwner"))  
static AIMODULE_API void SetBlackboardValueAsObject(UBTNode* NodeOwner, const FBlackboardKeySelector& Key, UObject* Value);
```

## Example

```cpp
UBTFunctionLibrary::SetBlackboardValueAsObject(this, TargetToFollowSelector, ClosesActor);
```