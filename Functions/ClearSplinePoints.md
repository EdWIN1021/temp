---
tags:
  - Function
Belongs to: "[[USplineComponent]]"
Parameter of: 
Return: 
Interface: 
Description: Clears all the points in the spline
---

## Declaration

```cpp
/** Clears all the points in the spline */ 
UFUNCTION(BlueprintCallable, Category = Spline) 
ENGINE_API void ClearSplinePoints(bool bUpdateSpline = true);
```

## Example

```cpp
Spline->ClearSplinePoints();
```