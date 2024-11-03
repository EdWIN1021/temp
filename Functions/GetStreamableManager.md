---
tags:
  - Function
Belongs to: "[[UAssetManager]]"
Return: 
Interface: 
Description: Accesses the StreamableManager used by this Asset Manager. Static for easy access
---

## Declaration

```cpp
static FStreamableManager& GetStreamableManager() { return Get().StreamableManager; }
```

## Example

```cpp
UAssetManager::GetStreamableManager().RequestAsyncLoad(
  CharacterStartUpData.ToSoftObjectPath(),
  FStreamableDelegate::CreateLambda(
    [this]()
	{
    	if(UDataAsset_StartUpDataBase* LoadedData = CharacterStartUpData.Get())
		{
    		LoadedData->GiveToAbilitySystemComponent(WarriorAbilitySystemComponent);
		}
	}
  )
);
```