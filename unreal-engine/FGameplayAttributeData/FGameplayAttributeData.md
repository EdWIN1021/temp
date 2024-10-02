#UAttributeSet

- [[ReplicatedUsing]]
- [[AttributeAccessors]]

```cpp
UPROPERTY(BlueprintReadOnly, ReplicatedUsing = OnRep_<Attribute>)  
FGameplayAttributeData Attribute;
ATTRIBUTE_ACCESSORS(UAuraAttributeSet, Attribute);
```