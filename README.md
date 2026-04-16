# AI_NPC

A modular and high-performance **AI NPC System** for **Unreal Engine 5**. This repository provides a robust framework for creating intelligent non-player characters capable of environmental interaction, complex behavioral logic, and seamless integration with modern AI backends.

---

## 🚀 Key Features

* **Dynamic Decision Making:** Leverages UE5 Behavior Trees and the Environment Query System (EQS) for realistic spatial awareness.
* **Modular Architecture:** Easily swap logic sets for different NPC archetypes (e.g., Guards, Civilians, or Vendors).
* **Advanced Perception:** Fully integrated AI Perception components for sight, hearing, and touch stimuli.
* **Dialogue Framework:** Extensible system designed to bridge NPCs with LLM backends (like OpenAI or local models).
* **Optimized Core:** Core logic implemented in C++ for maximum performance, with Blueprint exposure for rapid iteration.

## 🛠️ Tech Stack

* **Engine:** Unreal Engine 5.x
* **Programming:** C++ / Blueprints
* **Version Control:** Git (LFS recommended for large assets)

## 📦 Installation

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/AI_NPC.git](https://github.com/YourUsername/AI_NPC.git)
    ```
2.  **Generate Project Files:** Right-click `AI_NPC.uproject` in your file explorer and select **"Generate Visual Studio project files."**
3.  **Build the Project:** Open the generated `.sln` file and build the solution in **Development Editor** configuration.
4.  **Launch:** Open the `.uproject` file to start the Unreal Editor.

## 📖 Quick Start

* **Placement:** Drag the `BP_Base_NPC` actor into your level.
* **Logic Assignment:** Assign a specific `BT_NPC_Behavior` asset to the AI Controller via the Details panel.
* **Navigation:** Ensure your level has a **Nav Mesh Bounds Volume** to enable movement.

## 🗺️ Roadmap

- [ ] Support for MetaHuman-specific animation blueprints.
- [ ] Direct C++ integration for local LLM inference.
- [ ] Advanced crowd simulation and group behavior logic.
