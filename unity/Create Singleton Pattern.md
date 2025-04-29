```csharp
public static GameMenu instance; 

void Awake() { 
	if (instance == null) { 
		instance = this;
		
		// Optional: Keeps the instance alive across scenes 
		 DontDestroyOnLoad(gameObject); 
	} 
	else if (instance != this) { 
		// Optional: Ensures only one instance exists
		Destroy(gameObject); 
	}
}

```