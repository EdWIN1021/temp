---
tags:
  - Property
Belongs to: "[[UProjectileMovementComponent]]"
Description: Initial speed of projectile. If greater than zero, this will override the initial Velocity value and instead treat Velocity as a direction
---

## Declaration

```cpp
UPROPERTY(EditAnywhere, BlueprintReadWrite, Category=Projectile) float InitialSpeed;
```

## Example

```cpp
ProjectileMovement->InitialSpeed = 550.f;
```