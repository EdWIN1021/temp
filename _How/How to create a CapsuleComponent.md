```cpp

// .h
class UCapsuleComponent* Capsule;
UCapsuleComponent* SecondCapsule;

//.cpp
#include "Components/CapsuleComponent.h"

Capsule = CreateDefaultSubobject<UCapsuleComponent>(TEXT("Capsule")); // -> forward declear
Capsule->SetCapsuleHalfHeight(20.f);
Capsule->SetCapsuleRadius(15.f);
```