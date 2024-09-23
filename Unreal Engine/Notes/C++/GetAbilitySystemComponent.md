```cpp title:.h
virtual UAbilitySystemComponent* GetAbilitySystemComponent() const override;
```


```cpp title:.cpp
UAbilitySystemComponent* AAuraCharacterBase::GetAbilitySystemComponent() const  
{  
    return AbilitySystemComponent;  
}
```