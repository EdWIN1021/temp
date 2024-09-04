```cpp
//.h
virtual void NativeUpdateAnimation(float DeltaTime) override;

//.cpp
void USlashAnimInstance::NativeUpdateAnimation(float DeltaTime)
{
	Super::NativeUpdateAnimation(DeltaTime);
}
```