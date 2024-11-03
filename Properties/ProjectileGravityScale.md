---
tags:
  - Property
Belongs to: "[[UProjectileMovementComponent]]"
Description: Custom gravity scale for this projectile. Set to 0 for no gravity.
---

## Declaration

```cpp
UPROPERTY(EditAnywhere, BlueprintReadWrite, Category=Projectile) float ProjectileGravityScale;
```

## Example

```cpp
ProjectileMovement->ProjectileGravityScale = 0.f;
```

