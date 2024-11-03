---
tags:
  - Function
Belongs to: "[[UAnimInstance]]"
Parameter of: 
Return: 
Interface: 
Description: Plays an animation montage. Returns the length of the animation montage in seconds. Returns 0.f if failed to play
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category = "Animation|Montage")
ENGINE_API float Montage_Play(
  UAnimMontage* MontageToPlay, 
  float InPlayRate = 1.f, 
  EMontagePlayReturnType ReturnValueType = EMontagePlayReturnType::MontageLength, 
  float InTimeToStartMontageAt=0.f, bool bStopAllMontages = true
);
```

## Example

```cpp
```

## Options
- 