- function will be called on clients when the property changes on the server

```cpp
UFUNCTION()  
void OnRep_<attribute>(const FGameplayAttributeData& <OldAttribute>) const;
```