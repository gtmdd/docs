# Gorilla Tag Mod Developer Documentation
> Version 2024.11

## Initialize your program
To create a mod, BepInEx expects a specific type of line in your code that will let it know your code is a mod. To do this, we use BepInPlugin, a flag that when called, asks for a UUID, name, and a version number. Here is a structure of the most basic initialization you can do:

```cs
using System;
using UnityEngine;
using BepInEx;

namespace Mod {
	public class ModInit {
		[BepInPlugin(“com.myname.gorillatag.mymod”, “My mod name”, “v1.0.0”)]
	}
}
```

This is the most basic you get. This code will compile, but it won’t do anything.
