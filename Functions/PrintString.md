---
tags:
  - Function
Belongs to: "[[UKismetSystemLibrary]]"
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
UFUNCTION(
	BlueprintCallable, 
	meta=(
		WorldContext="WorldContextObject", 
		CallableWithoutWorldContext, Keywords = "log print", 
		AdvancedDisplay = "2", 
		DevelopmentOnly
	), 
	Category="Development"
) 
static ENGINE_API void PrintString( 	
	const UObject* WorldContextObject,  	
	const FString& InString = FString(TEXT("Hello")),  	
	bool bPrintToScreen = true,  	
	bool bPrintToLog = true,  	
	FLinearColor TextColor = FLinearColor(0.0f, 0.66f, 1.0f),  	
	float Duration = 2.f, 
	const FName Key = NAME_None
);
```

## Example

```cpp
UKismetSystemLibrary::PrintString(this, FString("ActivateAbility (C++)"), true, true, FLinearColor::Yellow, 3);
```