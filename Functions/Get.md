---
tags:
  - Function
Belongs to: "[[UGameplayTagsManager]]"
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
/** Returns the global UGameplayTagsManager manager */ 
FORCEINLINE static UGameplayTagsManager& Get() { 	
	if (SingletonManager == nullptr) 	{ 		
		InitializeManager(); 	
	}  	
	return *SingletonManager; 
}
```

## Example

```cpp
UGameplayTagsManager::Get();
```