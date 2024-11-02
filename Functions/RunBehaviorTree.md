---
tags:
  - Function
Belongs to: "[[AAIController]]"
Parameter of: 
Return: 
Interface: 
Description: Starts executing behavior tree.
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category = "AI") 
AIMODULE_API virtual bool RunBehaviorTree(UBehaviorTree* BTAsset);
```

## Example

```cpp
AuraAIController->RunBehaviorTree(BehaviorTree);
```