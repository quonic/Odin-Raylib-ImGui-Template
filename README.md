# Odin Raylib + ImGui Template

A starter template for [Odin](https://odin-lang.org/) projects, pre-configured with [Raylib](https://www.raylib.com/) and [Dear ImGui](https://github.com/ocornut/imgui) bindings.

Available languages:
- [English/EN](README.md)
- [Русский/RU](README.ru.md)

> [!WARNING]
> At the moment, linux build is a bit [broken](https://github.com/fredtheking/Odin-Raylib-ImGui-Template/issues/1).

## Features

- Includes `imgui` + `imgui_impl_raylib`
- Minimal project structure
- Ready to build out of the box

## Requirements

- [Odin](https://odin-lang.org/docs/install) (All other dependencies are included)

## Build

On Windows:
```cpp
./build.bat
```
On Linux:
```bash
./build.sh
```

## Sources Used

- [imgui_impl_raylib](https://gist.github.com/lucaspoffo/a0d4192acd74d718e433ea0bafe17bc4) (slightly modified for compatibility)
- [odin-imgui](https://gitlab.com/L-4/odin-imgui)
