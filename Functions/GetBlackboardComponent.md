---
tags:
  - Function
Belongs to: "[[AAIController]]"
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
UBlackboardComponent* GetBlackboardComponent() { return Blackboard; }
```

## Example

```cpp
AuraAIController->GetBlackboardComponent()->InitializeBlackboard(*BehaviorTree->BlackboardAsset);
```

## Options
- 