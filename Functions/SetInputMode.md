---
tags:
  - Function
Belongs to: "[[APlayerController]]"
Parameter of: 
Return: 
Interface: 
Description: Setup an input mode
---

## Declaration

```cpp
ENGINE_API virtual void SetInputMode(const FInputModeDataBase& InData);
```

## Example

```cpp
// cursor behavior
FInputModeGameAndUI InputModeData;
InputModeData.SetLockMouseToViewportBehavior(EMouseLockMode::DoNotLock);
InputModeData.SetHideCursorDuringCapture(false);
SetInputMode(InputModeData);
```
