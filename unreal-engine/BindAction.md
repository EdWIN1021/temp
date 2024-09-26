

```cpp
FEnhancedInputActionEventBinding& BindAction<UserClass, VarTypes...>(
    const UInputAction* Action, 
    ETriggerEvent TriggerEvent, 
    UserClass* Object, 
    FEnhancedInputActionHandlerValueSignature::TMethodPtr<UserClass, VarTypes...> Func, 
    VarTypes... Vars)
```