```cpp
//.h
class UCameraComponnet;
UCameraComponnet* ViewCamera;

//.cpp
#include "Camera/CameraComponent.h"
ViewCamera = CreateDefaultSubobject<UCameraComponnet>(Text("ViewCamera"));
ViewCamera->SetupAttachment(SpringArm);
```