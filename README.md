# Cpp-Gameplay-Mechanics

A collection of gameplay mechanics implemented in C++ for **Unreal Engine 5**. This project serves as a portfolio demonstrating custom character logic, interaction systems, and object manipulation without relying heavily on Blueprints.

## 📝 About the Project

This repository focuses on core gameplay programming concepts. It implements a First-Person character capable of interacting with the world, managing a selection of items/objects, and manipulating physics objects.

**Engine Version:** Unreal Engine 5.x
**Language:** C++

## ✨ Key Features

*   **Interaction System:** Raycast-based (Line Trace) interaction logic to detect and use objects in the world. Configurable interaction distance.
*   **Item Selection System:** Logic for cycling through and selecting different items or weapons (`SelectThingNum`, `ChoosingThing`).
*   **Physics Interaction:** Implemented mechanics to pick up and throw objects with adjustable force (`StrengthThrow`).
*   **Object Management:** Systems to add or remove items from the character's current selection (`RemoveThing`).
*   **Custom Character Movement:** robust C++ implementation of standard movement (Walking, Jumping) and camera control.

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

*   **Unreal Engine 5**
*   **Visual Studio 2022**
*   **Git**

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Kierish/Cpp-Gameplay-Mechanics.git
    ```

2.  **Generate Project Files:**
    *   Right-click on the `.uproject` file.
    *   Select **"Generate Visual Studio project files"**.

3.  **Compile and Run:**
    *   Open the `.sln` file.
    *   Build the project (Ctrl+Shift+B).
    *   Press **F5** to launch the Editor.

## 🎮 Controls

*(Default bindings based on C++ Setup)*

| Action | Functionality |
| :--- | :--- |
| **W, A, S, D** | Movement |
| **Space Bar** | Jump |
| **E** | Interact (Line Trace) |
| **Mouse Wheel / Keys** | Select Item (Cycle Things) |
| **G / Drop Key** | Remove/Drop Thing |

## 📂 Project Structure

*   `/Config` - Input and Engine configuration.
*   `/Source` - C++ Classes (Character, Interacables, GameMode).
*   `/Content` - Assets and Blueprints derived from the C++ classes.

## 🤝 Contributing

Contributions are welcome!
1.  Fork the repository.
2.  Create a feature branch.
3.  Commit changes.
4.  Push to the branch and open a Pull Request.

## 📄 License

This project is open-source.

---
**Author:** [Kierish](https://github.com/Kierish)
