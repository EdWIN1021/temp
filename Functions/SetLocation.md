---
tags:
  - Function
Belongs to: "[[FTransform]]"
Parameter of: 
Return: 
Interface: 
Description: Set the translation of this transformation
---

## Declaration

```cpp
FORCEINLINE void SetLocation(const TVector<T>& Origin) {		 	
	Translation = VectorLoadFloat3_W0(&Origin); 	
	DiagnosticCheckNaN_Translate(); 
} 
```

## Example

```cpp
FTransform SpawnTransform;
SpawnTransform.SetLocation(SocketLocation);
```