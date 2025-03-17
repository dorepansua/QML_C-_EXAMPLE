# QtConsoleApp

A simple Qt-based console application using CMake. This project demonstrates how to set up a Qt 6 console application and link the Qt Core module.

## Features
- Uses **Qt 6** for a console application.
- Logs messages using both **C++ standard output (`std::cout`)** and **Qt's `qDebug()`**.
- Configured with **CMake** for easy build and dependency management.
- Uses an **environment variable (`Qt6_DIR`)** to configure the Qt path.

## Requirements
- **C++17 or later**
- **Qt 6.7.2** (or compatible version)
- **CMake 3.16+**
- **MSVC 2019 (or compatible compiler)**

## Setup & Build

### 1. Set Up the Qt Path in Environment Variables

#### **Windows (CMD or PowerShell)**
Set the Qt path as an environment variable:

##### **Command Prompt (cmd)**
```cmd
setx Qt6_DIR "C:\Qt\6.7.2\msvc2019_64"
