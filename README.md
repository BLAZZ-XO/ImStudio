


# ImStudio
[![Build Status](https://github.com/Raais/ImStudio/actions/workflows/linux.yml/badge.svg)](https://github.com/Raais/ImStudio/actions?workflow=linux)

Real-time GUI layout creator/editor for [Dear ImGui](https://github.com/ocornut/imgui)

![Screenshot with all windows](https://user-images.githubusercontent.com/64605172/140092885-4e1970d6-2518-4c42-a9a0-c14725931aea.png)

![Making a simple layout](https://user-images.githubusercontent.com/64605172/140092697-c7760d6e-6f5a-4dd0-b208-919e9647c117.gif)

Inspired by [Code-Building/ImGuiBuilder](https://github.com/Code-Building/ImGuiBuilder)

## Features

 - Drag edit
 - Property edit
 - Covers most of the commonly used default widgets (primitives, data inputs, and other miscellaneous)
 - Child windows
 - Real-time generation
 - Export to clipboard
 - Useful tools (Style & Color export, Demo Window, etc.)
 - Helpful resources (external)
 
## Installation

### Dependencies

 - [GLFW](https://www.glfw.org/download) \
 <sub><sup> **Ubuntu Linux:** sudo apt-get install libglfw3 libglfw3-dev </sub></sup>\
 <sub><sup> **Arch Linux:** sudo pacman -S glfw </sub></sup>\
 <sub><sup> **MacOS:** brew install glfw </sub></sup>

### Instructions
```bash
git clone https://github.com/Raais/ImStudio
cd ImStudio
make
./ImStudio
```
---
###### Ubuntu one-liner (not recommended)
```bash
#tested 20.04 | this is mainly for quickly testing on a VM
sudo apt-get -y update && sudo apt-get -y install build-essential git libglfw3 libglfw3-dev && git clone https://github.com/Raais/ImStudio && cd ImStudio && make -j2 && ./ImStudio
```

## Credits
Thanks to [Omar](https://github.com/ocornut) for [Dear ImGui](https://github.com/ocornut/imgui).\
Thanks to [Code-Building](https://github.com/Code-Building) for the inspiration.
