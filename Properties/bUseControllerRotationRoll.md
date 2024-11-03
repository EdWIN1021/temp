---
tags:
  - Property
Struct: 
Belongs to: "[[APawn]]"
Getter: 
Description: If true, this Pawn's roll will be updated to match the Controller's ControlRotation roll, if controlled by a PlayerController.
---

## Declaration

```cpp
UPROPERTY(EditAnywhere, BlueprintReadWrite, Category=Pawn) 
uint32 bUseControllerRotationRoll:1;  
```

## Example

```cpp
bUseControllerRotationRoll = false;
```

