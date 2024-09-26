```cpp
#define ATTRIBUTE_ACCESSORS(ClassName, PropertyName) \  
    GAMEPLAYATTRIBUTE_PROPERTY_GETTER(ClassName, PropertyName) \  
    GAMEPLAYATTRIBUTE_VALUE_GETTER(PropertyName) \  
    GAMEPLAYATTRIBUTE_VALUE_SETTER(PropertyName) \  
    GAMEPLAYATTRIBUTE_VALUE_INITTER(PropertyName)

/*  
  ATTRIBUTE_ACCESSORS(UMyHealthSet, Health)
  static FGameplayAttribute UMyHealthSet::GetHealthAttribute();  
  FORCEINLINE float UMyHealthSet::GetHealth() const;  
  FORCEINLINE void UMyHealthSet::SetHealth(float NewVal);  
  FORCEINLINE void UMyHealthSet::InitHealth(float NewVal);
*/
```

