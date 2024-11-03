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
UPROPERTY(EditDefaultsOnly)

// instance detail
UPROPERTY(EditDefaultsOnly)

// both blueprint and instance detail
UPROPERTY(EditAnywhere)

UPROPERTY(EditAnywhere, BlueprintReadWrite)

//  BlueprintReadOnly: Makes the property read-only in Blueprints.
UPROPERTY(EditAnywhere, BlueprintReadOnly, Category = "Combat", meta=(AllowPrivateAccess = "true"))

UPROPERTY(BlueprintReadWrite, meta=(ExposeOnSpawn = true))

// visiable only
UPROPERTY(VisibleDefaultOnly)

UPROPERTY(VisibleInstanceOnly)

UPROPERTY(VisibleAnywhere)

UPROPERTY(BlueprintReadOnly, ReplicatedUsing = OnRep_Health, Category = "Vital Attributes")
```

