---
tags:
  - Function
Class: "[[AActor]]"
Parameters: "[[FVector]]"
Return: 
Interface: 
Description: 
Type:
---

## Declaration

```cpp
bool SetActorLocation( 
	const FVector& NewLocation, 
	bool bSweep = false, 
	FHitResult* OutSweepHitResult = nullptr, 
	ETeleportType Teleport = ETeleportType::None)
```

## Example

```cpp
SetActorLocation(FVector(0.f, 0.f, 50.f));
```

## Getter

```cpp
```

## Options
- 