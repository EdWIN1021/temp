---
tags:
  - Function
Belongs to: "[[UAbilitySystemComponent]]"
Parameter of: "[[EGameplayEffectReplicationMode]]"
Return: 
Interface: 
Description: 
Type:
---

## Declaration

```cpp
virtual void SetReplicationMode(EGameplayEffectReplicationMode NewReplicationMode)
```

## Example

```cpp
// Player 
AbilitySystemComponent->SetReplicationMode(EGameplayEffectReplicationMode::Mixed);

//AI
AbilitySystemComponent->SetReplicationMode(EGameplayEffectReplicationMode::Minimal);
```

## Getter

```cpp
```

## Options
- 