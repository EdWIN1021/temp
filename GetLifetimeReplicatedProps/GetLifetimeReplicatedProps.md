#UAttributeSet
- This function is responsible for defining which properties should be replicated over the network.
- [[DOREPLIFETIME_CONDITION_NOTIFY]]
```cpp
virtual void GetLifetimeReplicatedProps(TArray<FLifetimeProperty>& OutLifetimeProps) const override
```

```cpp
void U<Project>AttributeSet::GetLifetimeReplicatedProps(TArray<FLifetimeProperty>& OutLifetimeProps) const  
{  
    Super::GetLifetimeReplicatedProps(OutLifetimeProps);  
    DOREPLIFETIME_CONDITION_NOTIFY(U<Project>AttributeSet, <Attribute>, COND_None, REPNOTIFY_Always);   
}
```