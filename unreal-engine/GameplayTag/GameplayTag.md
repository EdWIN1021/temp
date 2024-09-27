Project Settings -> GameplayTags->Manage Gameplay Tags

```cpp title:.h
namespace <Project>GameplayTags  
{  
    /**  Input Tags **/  
    UE_DEFINE_GAMEPLAY_TAG(InputTag_<Tag>, "InputTag.<Tag>")  
}
```

```cpp title:.cpp
#include "NativeGameplayTags.h"  
namespace <Project>GameplayTags  
{  
    /**  Input Tags **/  
    <Project>_API UE_DECLARE_GAMEPLAY_TAG_EXTERN(InputTag_<Tag>)  
}
```