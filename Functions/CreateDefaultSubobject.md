---
tags:
  - Function
Belongs to: "[[UObject]]"
Parameter of: 
Return: 
Interface: 
Description: Create a component or subobject that will be instanced inside all instances of this class.
---

## Declaration

```cpp
template<class TReturnType> 
TReturnType* CreateDefaultSubobject(FName SubobjectName, bool bTransient = false) {  
	UClass* ReturnType = TReturnType::StaticClass();   
	return static_cast<TReturnType*>(CreateDefaultSubobject(
				SubobjectName, 
				ReturnType, 
				ReturnType, /*bIsRequired =*/ true, 
				bTransient
				)
			); 
}
```

## Example

```cpp
```

## Options
- 