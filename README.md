# KiCad Demo Project

This repository contains a demonstration project for KiCad, including custom libraries and footprints as submodules.

## Project Description
A demo project showcasing KiCad's capabilities for PCB design and electronic schematic creation.

## Prerequisites
- Git
- KiCad (latest version recommended)

## Installation

### Cloning the Repository
There are two methods to clone this repository with its submodules:

#### Method 1: Clone with Submodules (Recommended)
```bash
git clone --recursive https://github.com/ionutms/KiCad_Demo_Project.git
```

#### Method 2: Clone and Initialize Submodules Separately
```bash
git clone https://github.com/ionutms/KiCad_Demo_Project.git
cd KiCad_Demo_Project
git submodule update --init
```

### Updating Submodules
If you need to update the submodules to their latest versions:
```bash
git submodule update --remote
```

## Usage
1. Open KiCad
2. File -> Open Project
3. Navigate to the cloned repository
4. Open the .kicad_pro file
