```cpp
// blueprint
UPROPERTY(EditDefaultsOnly)

// instance detail
UPROPERTY(EditDefaultsOnly)

// both blueprint and instance detail
UPROPERTY(EditAnywhere)

UPROPERTY(EditAnywhere, BlueprintReadWrite)

//  BlueprintReadOnly: Makes the property read-only in Blueprints.
UPROPERTY(EditAnywhere, BlueprintReadOnly, Category = "Combat", meta=(AllowPrivateAccess = "true"))

// visiable only
UPROPERTY(VisibleDefaultOnly)

UPROPERTY(VisibleInstanceOnly)

UPROPERTY(VisibleAnywhere)


```