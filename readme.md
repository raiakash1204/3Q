# 🎛️ SimpleEQ JUCE Audio Plugin

A lightweight audio plugin built with modern C++ and the JUCE framework, following the MatKat Music “Learn Modern C++ by Building an Audio Plugin” tutorial :contentReference[oaicite:1]{index=1}.

## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Dependencies](#dependencies)  
- [Setup & Build](#setup--build)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Development Notes](#development-notes)  
- [License](#license)

---

## Overview

This project explores building a classic EQ plugin from scratch:

- Implemented using **JUCE** and **modern C++17**
- Learn-to-code audio nodes like **low-cut**, **high-cut**, and **peak filters**
- Fully functional **GUI controls** (sliders, knobs) mapped to DSP backbone
- Compilable as a **VST3/AU plugin** deployable in any DAW or plugin host

Ideal for students and hobbyists diving into C++ Audio Programming.

---

## Features

- 🎚️ Adjustable **Low-Cut**, **High-Cut**, and **Peak** filters  
- Responsive **GUI controls** with real-time DSP parameter mapping  
- Built using JUCE's `AudioProcessorValueTreeState`  
- Modular, scalable codebase — ready for additional DSP modules (compressors, modulation, etc.)

---

## Dependencies

- [JUCE Framework](https://juce.com) (GitHub or official)  
- C++17 compatible compiler (GCC, Clang, MSVC)  
- Supported IDEs: **Visual Studio**, **Xcode**, **CLion**, etc.

---

## Setup & Build

1. **Clone repo**  
   ```bash
   git clone https://github.com/yourusername/simple-eq-juce-plugin.git
   cd simple-eq-juce-plugin
