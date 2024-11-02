---
tags:
  - Function
  - Override
Belongs to: "[[UObject]]"
Parameter of: 
Return: 
Interface: 
Description: This function is responsible for defining which properties should be replicated over the network
Type:
---

## Declaration

```cpp
COREUOBJECT_API virtual void GetLifetimeReplicatedProps( TArray< class FLifetimeProperty > & OutLifetimeProps ) const;
```

## Example

```cpp
void U<Project>AttributeSet::GetLifetimeReplicatedProps(TArray<FLifetimeProperty>& OutLifetimeProps) const {}
```
