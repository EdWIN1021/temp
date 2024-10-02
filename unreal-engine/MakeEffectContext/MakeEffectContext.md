- This creates an Effect Context, which carries information about the context of the effect (like who is applying it).
-  TargetASC: [[UAbilitySystemComponent]]
```cpp
FGameplayEffectContextHandle EffectContextHandle = TargetASC->MakeEffectContext(); 
EffectContextHandle.AddSourceObject(this);
```