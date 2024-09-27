- Specifies the property should be replicated without any conditions, and will notify clients whenever it changes REPNOTIFY_Always.
```cpp
DOREPLIFETIME_CONDITION_NOTIFY(UAuraAttributeSet, Health, COND_None, REPNOTIFY_Always);
```