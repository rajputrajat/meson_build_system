# Platform agnostic build system using Meson, Ninja and llvm

## Commands

### set compiler flags

```powershell
let-env CXX = clang++
let-env CC = clang
```

### meson build

```powershell
meson build
```

* here ./build is directory which will be created automatically for keep all build files

### compile

```powershell
cd build
meson compile
#or
ninja
```

### run

```powershell
./build/simple.exe
```
