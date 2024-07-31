```cpp
Weapon = CreateDefaultSubobject<USkeletalMeshComponent>("Weapon");
Weapon->SetupAttachment(GetMesh(), FName("WeaponHandSocket"));
Weapon->SetCollisionEnabled(ECollisionEnabled::NoCollision);
```