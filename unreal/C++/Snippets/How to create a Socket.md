```cpp
// create a weapon socket for a charactor
Weapon = CreateDefaultSubobject<USkeletalMeshComponent>("Weapon");
Weapon->SetupAttachment(GetMesh(), FName("WeaponHandSocket"));
Weapon->SetCollisionEnabled(ECollisionEnabled::NoCollision);
```