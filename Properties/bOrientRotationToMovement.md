---
tags:
  - Property
Struct: 
Belongs to: 
Getter: "[[UCharacterMovementComponent]]"
Description: If true, rotate the Character toward the direction of acceleration, using RotationRate as the rate of rotation change. Overrides UseControllerDesiredRotation.
---

## Declaration

```cpp
UPROPERTY(Category="Character Movement (Rotation Settings)", EditAnywhere, BlueprintReadWrite) uint8 bOrientRotationToMovement:1;   
```

## Example

```cpp
GetCharacterMovement()->bOrientRotationToMovement = true;
```