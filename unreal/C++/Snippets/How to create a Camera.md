```cpp
//.h
class UCameraComponnet;

UPROPERTY(VisibleAnywhere)
UCameraComponnet* ViewCamera;

//.cpp
#include "Camera/CameraComponent.h"
ViewCamera = CreateDefaultSubobject<UCameraComponnet>(Text("ViewCamera"));
ViewCamera->SetupAttachment(CameraBoom);

```