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
GAMEPLAYTAGS_API FGameplayTag AddNativeGameplayTag(
	FName TagName, 
	const FString& TagDevComment = TEXT("(Native)")
);
```

## Example

```cpp
GameplayTags.Attributes_Primary_Strength = UGameplayTagsManager::Get()
	.AddNativeGameplayTag(
		FName("Attributes.Primary.Strength"), 	
		FString("Increases physical damage") 	
	);
```