```cpp

//.h
class USkeletalMeshComponent;
USkeletalMeshComponent* BridMesh;

//.cpp
#include "Components/SkeletalMeshComponent.h"
BirdMesh = CreateDefaultSubobject<SkeletalMeshComponent>(TEXT("BirdMesh"));
BirdMesh->SetupAttachment(GetRootComponent());
``` 