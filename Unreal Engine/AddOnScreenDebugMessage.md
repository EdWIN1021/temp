```cpp
if(GEngine) {
  FString Message = FString::Printf(TEXT("DeltaTime: %f"), DeltaTime);
  GEngine->AddOnScreenDebugMessage(1, 60.f, FColor::Cyan, Message);
}
```