```cpp
// blueprint
UPROPERTY(EditDefaultsOnly)

// instance detail
UPROPERTY(EditDefaultsOnly)

// both blueprint and instance detail
UPROPERTY(EditAnywhere)

// visiable only
UPROPERTY(VisibleDefaultOnly)

UPROPERTY(VisibleInstanceOnly)

UPROPERTY(VisibleAnywhere)

protected:
  UPROPERTY(EditAnywhere, BlueprintReadWrite)
  
private:
  UPROPERTY(EditAnywhere, BlueprintReadOnly, Category = "Combat", meta=(AllowPrivateAccess = "true"))

```