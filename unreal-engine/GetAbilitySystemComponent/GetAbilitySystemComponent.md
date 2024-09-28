
## IAbilitySystemInterface
```cpp
virtual UAbilitySystemComponent* GetAbilitySystemComponent() const override;

UAbilitySystemComponent* AAuraCharacterBase::GetAbilitySystemComponent() const  
{  
  return AbilitySystemComponent;  
}
```

## AbilitySystemBlueprintLibrary
```cpp 
static UAbilitySystemComponent* GetAbilitySystemComponent(AActor* Actor);
UAbilitySystemComponent* TargetASC = UAbilitySystemBlueprintLibrary::GetAbilitySystemComponent(Target);
```


