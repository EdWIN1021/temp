---
tags:
  - Function
Belongs to: "[[UAnimNotify]]"
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
UFUNCTION(
	BlueprintImplementableEvent, 
	meta=(AutoCreateRefTerm="EventReference")
) 
ENGINE_API bool Received_Notify(
	USkeletalMeshComponent* MeshComp,
	UAnimSequenceBase* Animation, 
	const FAnimNotifyEventReference& EventReference) const;
```

## Example

```cpp
```