---
tags:
  - Function
Class: "[[UAnimInstance]]"
Parameters: 
Return: 
Interface: 
Description: It is part of the UAnimInstance class and is used to get a reference to the APawn that owns the animation instance.
Type:
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable) 
virtual APawn* TryGetPawnOwner() const
```

## Example

```cpp
APawn* PawnOwner = TryGetPawnOwner();
```

## Getter

```cpp
```

## Options
- [[GetCharacterMovement]]