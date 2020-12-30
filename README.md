# prebuild-windows-dependencies

Stores Win64 builds of llvm (https://github.com/llvm/llvm-project), glfw(https://github.com/glfw/glfw) and openal (https://github.com/kcat/openal-soft)

Due to the windows chocolately distributions being unsuitable for use (missing the cmake dependencies)

```
openal @ 15e05fcef882e3d50104db39d38019165c7995f9
llvm @ llvmorg-11.0.0
glfw @ 0b9e48fa3df9c184ff1abfb2452fd1a4b696ecd8
```

These are used by https://github.com/SavourySnaX/EDL and https://github.com/SavourySnaX/Slipstream in the github actions
