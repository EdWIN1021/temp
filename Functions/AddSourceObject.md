---
tags:
  - Function
Belongs to: "[[FGameplayEffectContextHandle]]"
Parameter of: 
Return: 
Interface: 
Description: Sets the object this effect was created from.
Type:
---

## Declaration

```cpp
void AddSourceObject(const UObject* NewSourceObject)
{
  if (IsValid())
  {
    Data->AddSourceObject(NewSourceObject);
  }
}
```

## Example

```cpp
PrimaryAttributesContextHandle.AddSourceObject(AvatarActor);
```