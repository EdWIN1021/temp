#UAbilitySystemComponent
```cpp
virtual void SetReplicationMode(EGameplayEffectReplicationMode NewReplicationMode)
```

## Player
```cpp
AbilitySystemComponent->SetReplicationMode(EGameplayEffectReplicationMode::Mixed);
```

## AI
```cpp
AbilitySystemComponent->SetReplicationMode(EGameplayEffectReplicationMode::Minimal);
```