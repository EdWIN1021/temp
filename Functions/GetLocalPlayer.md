---
tags:
  - Function
Belongs to: "[[APlayerController]]"
Parameter of: 
Return: 
Interface: 
Description: Returns the ULocalPlayer for this controller if it exists, or null otherwise
Type:
---


## Declaration

```cpp
ENGINE_API class ULocalPlayer* GetLocalPlayer() const;
```

## Example

```cpp
UEnhancedInputLocalPlayerSubsystem* Subsystem = ULocalPlayer::GetSubsystem<UEnhancedInputLocalPlayerSubsystem>(GetLocalPlayer());
```