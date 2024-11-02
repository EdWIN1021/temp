---
tags:
  - Function
Belongs to: "[[UBlackboardComponent]]"
Parameter of: 
Return: 
Interface: 
Description: setup component for using given blackboard asset, returns true if blackboard is properly initialized for specified blackboard data
---

## Declaration

```cpp
AIMODULE_API bool InitializeBlackboard(UBlackboardData& NewAsset);
```

## Example

```cpp
AuraAIController->GetBlackboardComponent()->InitializeBlackboard(*BehaviorTree->BlackboardAsset);
```