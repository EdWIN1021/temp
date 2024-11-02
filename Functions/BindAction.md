---
tags:
  - Function
Belongs to: "[[UEnhancedInputComponent]]"
Parameter of: 
Return: 
Interface: 
Description: 
Type:
---


## Declaration

```cpp
FEnhancedInputActionEventBinding& BindAction<UserClass, VarTypes...>(
    const UInputAction* Action, 
    ETriggerEvent TriggerEvent, 
    UserClass* Object, 
    FEnhancedInputActionHandlerValueSignature::TMethodPtr<UserClass, VarTypes...> Func, 
    VarTypes... Vars)
```

## Example

```cpp
EnhancedInputComponent->BindAction(MoveAction, ETriggerEvent::Triggered, this, &<Project>PlayerController::Move);
```

## Getter

```cpp
```

## Options
- 