---
tags:
  - Function
Belongs to: "[[FInputModeGameAndUI]]"
Parameter of: 
Return: 
Interface: 
Description: Whether to hide the cursor during temporary mouse capture caused by a mouse down
---

## Declaration

```cpp
FInputModeGameAndUI& SetHideCursorDuringCapture(bool InHideCursorDuringCapture) { 
  bHideCursorDuringCapture = InHideCursorDuringCapture; 
  return *this; 
}
```

## Example

```cpp
FInputModeGameAndUI InputModeData;
InputModeData.SetHideCursorDuringCapture(false);
```
