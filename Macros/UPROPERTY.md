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
/* 
	It allows you to make a property editable in the Blueprint Editor's defaults panel 
	but prevents it from being modified during runtime or in instances of the Blueprint. 
*/
UPROPERTY(EditDefaultsOnly)

// instance detail
UPROPERTY(EditDefaultsOnly)

// both blueprint and instance detail
UPROPERTY(EditAnywhere)

UPROPERTY(EditAnywhere, BlueprintReadWrite)

//  BlueprintReadOnly: Makes the property read-only in Blueprints.
UPROPERTY(EditAnywhere, BlueprintReadOnly, Category = "Combat", meta=(AllowPrivateAccess = "true"))

// visiable only
UPROPERTY(VisibleDefaultOnly)

UPROPERTY(VisibleInstanceOnly)

UPROPERTY(VisibleAnywhere)

UPROPERTY(BlueprintReadOnly, ReplicatedUsing = OnRep_Health, Category = "Vital Attributes")
```

## Options
- 