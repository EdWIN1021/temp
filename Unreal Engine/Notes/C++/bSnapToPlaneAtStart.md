- & ensures the character's position is aligned with a **specific plane** (like the XY plane) at the start of the game or when the character spawns. It doesn't handle vertical alignment (e.g., snapping to terrain or the ground).

```cpp
GetCharacterMovement()->bSnapToPlaneAtStart = true;
```