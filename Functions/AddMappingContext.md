---
tags:
  - Function
Class: 
Parameters: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, BlueprintCosmetic, Category = "Input", meta=(AutoCreateRefTerm = "Options")) 
virtual void AddMappingContext( 
	const UInputMappingContext* MappingContext, 
	int32 Priority, 
	const FModifyContextOptions& Options = FModifyContextOptions());
```

## Example

```cpp
Subsystem->AddMappingContext(AuraContext, 0);
```

## Options
- 