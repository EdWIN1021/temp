---
tags:
  - Macro
Description: 
Belongs to:
---

## Declaration

```cpp

```

## Example

```cpp
UFUNCTION(BlueprintCallable)

UFUNCTION(BlueprintPure)

UFUNCTION(BlueprintImplementableEvent)

// Declare a function that can be implemented both in C++ and in Blueprints 
UFUNCTION(BlueprintNativeEvent)

UFUNCTION( meta = (HidePin = "OwningAbility", DefaultToSelf = "OwningAbility", BlueprintInternalUseOnly = "true"))

//This specifier means that the function will be called on the server and then replicated to all clients.
UFUNCTION(NetMulticast, Reliable)

// OutConfirmType is a Enum
UFUNCTION(meta = (DisplayName = "Does Actor Have Tag", ExpandEnumAsExecs = "OutConfirmType")) 

// BlueprintImplementableEvent -> dont need to make virtual
UFUNCTION(BlueprintImplementableEvent, BlueprintCallable)
```
