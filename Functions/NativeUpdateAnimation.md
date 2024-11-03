---
tags:
  - Function
Belongs to: "[[UAnimInstance]]"
Parameter of: 
Return: 
Interface: 
Description: Native update override point. It is usually a good idea to simply gather data in this step and for the bulk of the work to be done in NativeThreadSafeUpdateAnimation.
---

## Declaration

```cpp
ENGINE_API virtual void NativeUpdateAnimation(float DeltaSeconds);
```

## Example
```cpp
void USlashAnimInstance::NativeUpdateAnimation(float DeltaTime){    
	Super::NativeUpdateAnimation(DeltaTime);
}
```

