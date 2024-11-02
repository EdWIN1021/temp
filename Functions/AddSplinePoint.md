---
tags:
  - Function
Belongs to: "[[USplineComponent]]"
Parameter of: 
Return: 
Interface: 
Description: Adds a point to the spline
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category = Spline) 
ENGINE_API void AddSplinePoint(const FVector& Position, ESplineCoordinateSpace::Type CoordinateSpace, bool bUpdateSpline = true);
```

## Example

```cpp
Spline->AddSplinePoint(PointLoc, ESplineCoordinateSpace::World);
```