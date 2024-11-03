---
tags:
  - Property
Struct: 
Belongs to: "[[UCharacterMovementComponent]]"
Getter: 
Description: Deceleration when walking and not applying acceleration. This is a constant opposing force that directly lowers velocity by a constant value.
---

## Declaration

```cpp
UPROPERTY(
	Category="Character Movement: Walking",  
	EditAnywhere,  	
	BlueprintReadWrite,  	
	meta=(ClampMin="0", UIMin="0") 
) 
float BrakingDecelerationWalking'
```

## Example

```cpp
GetCharacterMovement()->BrakingDecelerationWalking = 2000.f;
```

## Getter

```cpp
```

## Options
- 