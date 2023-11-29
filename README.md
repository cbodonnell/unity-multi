# Unity Multiplayer

This repo has some basic examples of multiplayer concepts in Unity.

## Building

Run the following command to build the project for Windows:

```bash
UNITY='path/to/Unity.exe'
$UNITY -quit -batchmode -nographics -logFile - -executeMethod Builder.Build -projectPath .
```

Build Script - `Assets/Editor/Builder.cs`
