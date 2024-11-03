---
tags:
  - Function
Belongs to: "[[FInputModeGameAndUI]]"
Parameter of: 
Return: 
Interface: 
Description: Sets the mouse locking behavior of the viewport
---

## Declaration

```cpp
FInputModeGameAndUI& SetLockMouseToViewportBehavior(EMouseLockMode InMouseLockMode) { MouseLockMode = InMouseLockMode; return *this; }
```

## Example

```cpp
FInputModeGameAndUI InputModeData;
InputModeData.SetLockMouseToViewportBehavior(EMouseLockMode::DoNotLock);
```

