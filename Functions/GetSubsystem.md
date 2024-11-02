---
tags:
  - Function
Belongs to: "[[ULocalPlayer]]"
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
template <typename TSubsystemClass> 
static FORCEINLINE TSubsystemClass* GetSubsystem(const ULocalPlayer* LocalPlayer) {   
	if (LocalPlayer){     
		return LocalPlayer->GetSubsystem<TSubsystemClass>();   
	}   
	return nullptr; 
}
```

## Example

```cpp
UEnhancedInputLocalPlayerSubsystem* Subsystem = ULocalPlayer::GetSubsystem<UEnhancedInputLocalPlayerSubsystem>(GetLocalPlayer());
```

## Options
- 