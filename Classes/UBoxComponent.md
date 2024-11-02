---
tags:
  - Class
Derived from: "[[UShapeComponent]]"
Initialization: 
Has: 
Declaration: 
Description:
---

## Declaration

```cpp
UPROPERTY(VisibleAnywhere, BlueprintReadOnly, Category = "Collision") 
UBoxComponent* BoxCollisionComponent;
```

## Example

```cpp
BoxCollisionComponent = CreateDefaultSubobject<UBoxComponent(TEXT("BoxCollisionComponent"));
```