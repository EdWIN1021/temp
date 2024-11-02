---
tags:
  - Function
Belongs to: "[[AActor]]"
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
ENGINE_API void FinishSpawning(
	const FTransform& Transform,  	
	bool bIsDefaultTransform = false,  	
	const FComponentInstanceDataCache* InstanceDataCache = nullptr,  	
	ESpawnActorScaleMethod TransformScaleMethod = ESpawnActorScaleMethod::OverrideRootScale
);
```

## Example

```cpp
Projectile->FinishSpawning(SpawnTransform);
```