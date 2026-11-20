# TowerGenerator

TowerGenerator is a tool designed to quickly create modular city tower buildings from a collection of prefab pieces including ground floors, mid floors, roofs, fire escapes, and rooftop decor. Originally intended for use with Synty's Polygon City pack, the tool supports any modular prefab set with similar structure, enabling fast iteration and regeneration of building designs.

---

## Features

- **Modular Prefab Assembly**  
  Automatically build towers by stacking prefab pieces categorized as ground floors, mid floors, roofs, and additional elements like fire escapes and rooftop decor.

- **Automatic Prefab Categorization**  
  Scans your project library and suggests prefab categories to quickly organize and manage your building pieces.

- **One-Click Tower Generation and Regeneration**  
  Generate a complete tower with a single click and quickly iterate different variations using the regenerate function.

- **Supports Custom Modular Prefabs**  
  While optimized for Synty's Polygon City pack, it can work with other custom modular building pieces.

---

## Who is this for?

- Hobbyists and indie developers seeking to populate city scenes efficiently.
- Users of Synty Assets wanting to streamline building assembly.
- Level designers needing rapid prototyping of tower buildings.

---

## Benefits

- **Save time:** Automates prefab placement to remove manual stacking.
- **Quick iteration:** Easily regenerate tower designs to test different looks.
- **Flexible workflow:** Add or remove pieces from your library at any time to customize your building options.

---

## Installation

1. Import the TowerGenerator package into your Unity project.
2. Open the TowerGenerator window from the Unity Editor menu.
3. Allow the tool to scan and categorize your prefab library automatically.
4. Customize your prefab collection by adding or removing pieces as needed.

---

## Usage

### Building Piece Categories

TowerGenerator organizes prefabs into categories defined by the `BuildingPieceCategory` enum:

- Ground Floor
- Mid Floor
- Roof
- Fire Escape
- Roof Decor

These categories help the system determine how to stack pieces into a coherent tower.

### Creating a Tower

1. Populate your prefab library with building pieces.
2. Click the **Generate Tower** button in the TowerGenerator interface.
3. Use the **Regenerate** button to quickly create new variations of the tower design.

### Editing Prefab Library

Modify your prefab library anytime in the TowerGenerator interface or use the Library Builder window (`LibraryBuilderWindow`) to manage your collection.

---

## API Overview

- **BuildingPieceCategory (enum)**  
  Defines the type of prefab piece (e.g., ground floor, roof).

- **BuildingPieceCategoryExtensions (class)**  
  Extension methods to assist with piece category handling.

- **BuildingPieceLibrary (class)**  
  A `ScriptableObject` managing the collection of prefab pieces.

- **BuildingPieceSlot (struct)**  
  Represents a slot for a building piece within the tower structure.

- **ModularBuilding (class)**  
  Core component that assembles the tower at runtime or in-editor.

- **Custom Editor Classes (`BuildingPieceLibraryEditor`, `LibraryBuilderWindow`, `ModularBuildingEditor`)**  
  Editor tools to help create and manage building pieces and towers within the Unity Editor environment.

---

## Recommended Complementary Assets

- **Editor Tools - Developer Essentials**  
  An additional editor-based toolkit designed to speed up development workflows.  
  [Publisher page on Asset Store](https://assetstore.unity.com/packages/package/382386)

---

## Support and Resources

- Visit the [official website](https://chrisburns.com.au) for more info.
- Join the [support Discord server](https://discord.com/invite/ajDgWPmSBS) for community help and updates.
- Explore other assets by the publisher on the [Unity Asset Store](https://assetstore.unity.com/publishers/36542).

---

## Get Started

Explore the usage instructions above to integrate TowerGenerator into your city-building workflow. Quickly generate and regenerate tower buildings to speed up your level design process and experiment with architectural variations.

[View TowerGenerator on the Unity Asset Store](https://assetstore.unity.com/publishers/36542)

---

If you have questions or need further assistance, please join the support Discord or visit the website. Happy building!