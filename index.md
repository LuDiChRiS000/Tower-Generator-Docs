# Tower Generator

Tower Generator is a tool designed to quickly create modular city tower buildings by assembling prefab pieces including ground floors, mid floors, roofs, fire escapes, and rooftop decor. Initially optimized for use with Synty's Polygon City pack, Tower Generator also supports any modular prefab sets with a similar structure, enabling rapid iteration and regeneration of building designs.

---

## Features

- **Modular Prefab Assembly**  
  Automatically constructs towers by stacking prefab pieces categorized as ground floors, mid floors, roofs, fire escapes, and rooftop decor.

- **Automatic Prefab Categorization**  
  Scans your project library and suggests prefab categories to efficiently organize and manage building pieces.

- **One-Click Tower Generation and Regeneration**  
  Generate a complete tower with a single click and quickly iterate variations using the regenerate function.

- **Supports Custom Modular Prefabs**  
  While optimized for Synty’s Polygon City pack, it is compatible with other modular building prefab sets.

---

## Target Audience

- Hobbyists and indie developers looking to populate city scenes efficiently.
- Users of Synty Assets aiming to streamline building assembly workflows.
- Level designers requiring rapid prototyping and iteration of tower buildings.

---

## Benefits

- **Save Time:** Automates prefab placement to eliminate manual stacking.
- **Fast Iteration:** Quickly regenerate tower designs to explore different architectural variations.
- **Flexible Workflow:** Add or remove pieces from your prefab library anytime to customize building options.

---

## Installation

1. Import the Tower Generator package into your Unity project.
2. Open the Tower Generator window from the Unity Editor menu.
3. Allow the tool to scan and categorize your prefab library automatically.
4. Customize your prefab collection by adding or removing pieces as needed.

---

## Usage

### Building Piece Categories

Tower Generator organizes prefab pieces into the following categories (defined by the `BuildingPieceCategory` enum):

- Ground Floor  
- Mid Floor  
- Roof  
- Fire Escape  
- Roof Decor  

These categories guide the stacking logic to assemble coherent towers.

### Creating a Tower

1. Populate your prefab library with building pieces.
2. Click the **Generate Tower** button in the Tower Generator interface.
3. Use the **Regenerate** button to create new tower variations rapidly.

### Editing the Prefab Library

Manage your prefab collection directly within the Tower Generator interface or via the Library Builder window (`LibraryBuilderWindow`) to add, remove, or reorganize pieces.

---

## API Overview

- **BuildingPieceCategory (enum)**  
  Defines prefab piece types such as ground floor and roof.

- **BuildingPieceCategoryExtensions (class)**  
  Provides extension methods to assist with category operations.

- **BuildingPieceLibrary (class)**  
  A `ScriptableObject` managing a collection of building piece prefabs.

- **BuildingPieceSlot (struct)**  
  Represents individual slots for building pieces within the tower assembly.

- **ModularBuilding (class)**  
  The core component responsible for assembling the tower during runtime or within the editor.

- **Editor Tools**  
  - `BuildingPieceLibraryEditor` – Editor for managing building piece libraries.  
  - `LibraryBuilderWindow` – Window to build and modify prefab libraries.  
  - `ModularBuildingEditor` – Custom editor for the ModularBuilding component.

---

## Recommended Complementary Assets

- **Editor Tools - Developer Essentials**  
  An additional editor-based toolkit designed to accelerate development workflows.  
  [Publisher page on Asset Store](https://assetstore.unity.com/packages/package/382386)

---

## Support and Resources

- Visit the [official website](https://chrisburns.com.au) for detailed information.
- Join the [support Discord server](https://discord.com/invite/ajDgWPmSBS) for community help and updates.
- Explore other assets by the publisher on the [Unity Asset Store](https://assetstore.unity.com/publishers/36542).

---

## Get Started

Explore the usage instructions above to integrate Tower Generator into your city-building workflow. Quickly generate and regenerate tower buildings to accelerate your level design process and experiment with architectural variations.

[View Tower Generator on the Unity Asset Store](https://assetstore.unity.com/publishers/36542)

---

For questions or assistance, please join the support Discord or visit the website.