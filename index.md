# Tower Generator

Tower Generator is a tool designed to rapidly create modular city tower buildings by assembling prefab pieces including ground floors, mid floors, roofs, fire escapes, and rooftop decor. Originally optimized for Synty’s Polygon City pack, it also supports any modular prefab sets with a similar structure, enabling fast iteration and regeneration of building designs.

![Hero overview](images/hero-overview.png)

---

## Features

- **Modular Prefab Assembly**  
  Automatically constructs towers by stacking prefab pieces categorized as ground floors, mid floors, roofs, fire escapes, and rooftop decor.

- **Automatic Prefab Categorization**  
  Scans your project library and suggests prefab categories to efficiently organize and manage building pieces.

- **One-Click Tower Generation and Regeneration**  
  Generate complete towers easily and quickly iterate variations using the regenerate function.

- **Supports Custom Modular Prefabs**  
  Compatible with Synty’s Polygon City pack and other similar modular building prefab sets.

---

## Target Audience

- Hobbyists and indie developers populating city scenes efficiently.
- Users of Synty Assets seeking streamlined building assembly workflows.
- Level designers needing rapid prototyping and iteration of tower buildings.

---

## Benefits

- **Save Time:** Automates prefab placement to eliminate manual stacking.
- **Fast Iteration:** Quickly regenerate tower designs to explore architectural variations.
- **Flexible Workflow:** Customize your prefab library by adding or removing pieces at any time.

---

## Installation

1. Import the Tower Generator package into your Unity project.
2. Open the **Library Builder** window from the Unity Editor menu:  
   **Tools > Tower Generator > Library Builder**  
3. Allow the tool to scan and categorize your prefab library automatically.
4. Customize your prefab collection by adding or removing pieces as needed.

![Setup and configuration](images/setup-and-configuration.png)

---

## Usage

### Building Piece Categories

Tower Generator organizes prefab pieces into these categories (defined by the `BuildingPieceCategory` enum):

- Ground Floor  
- Mid Floor  
- Roof  
- Fire Escape  
- Roof Decor  

These categories determine stacking logic to assemble coherent towers.

### Creating and Placing a Tower

1. Open the **Library Builder** window and generate or update your prefab library asset that contains categorized building pieces.
2. Select and edit this prefab library asset in the Project window anytime to add or remove building pieces.
3. To place a tower in the scene, right-click in the **Hierarchy** window and select:  
   **Tower Generator > Modular Building**  
   This creates a GameObject with the `ModularBuilding` component configured.
4. Select the newly created GameObject, then use the **Generate Tower** button in the `ModularBuilding` component inspector to create the tower.
5. Click the **Regenerate** button to produce new tower variations quickly without modifying the library.

![Core workflow](images/core-workflow.png)

### Editing the Prefab Library

Manage your prefab pieces directly via the **Library Builder** editor window or by selecting the `BuildingPieceLibrary` asset in the Project window. Add, remove, or reorganize pieces to tailor the building options and appearance.

---

## API Overview

- **BuildingPieceCategory (enum)**  
  Enumerates prefab piece types: ground floor, mid floor, roof, fire escape, roof decor.

- **BuildingPieceCategoryExtensions (class)**  
  Provides helper methods for category-related operations.

- **BuildingPieceLibrary (class)**  
  A `ScriptableObject` managing collections of building piece prefabs.

- **BuildingPieceSlot (struct)**  
  Defines individual slots for building pieces within a tower assembly.

- **ModularBuilding (class)**  
  MonoBehaviour responsible for assembling towers at runtime or within the editor.

- **Editor Tools**  
  - `BuildingPieceLibraryEditor` – Custom inspector for prefab library management.  
  - `LibraryBuilderWindow` – EditorWindow for building and editing prefab libraries.  
  - `ModularBuildingEditor` – Custom inspector for the ModularBuilding component.

---

## Recommended Complementary Assets

- **Editor Tools - Developer Essentials**  
  An editor toolkit designed to accelerate development workflows.  
  [Publisher page on Asset Store](https://assetstore.unity.com/packages/package/382386)

---

## Support and Resources

- Visit the [official website](https://chrisburns.com.au) for detailed information.  
- Join the [support Discord server](https://discord.com/invite/ajDgWPmSBS) for community help and updates.  
- Explore more assets by the publisher on the [Unity Asset Store](https://assetstore.unity.com/publishers/36542).

---

## Getting Started

To start using Tower Generator:

1. **Build Your Prefab Library**  
   Open **Library Builder** via **Tools > Tower Generator > Library Builder**. The tool scans your project and suggests prefab categories for your modular building pieces. Save the generated `BuildingPieceLibrary` asset.

2. **Customize Your Library**  
   Select the prefab library asset in the Project window and add or remove pieces as needed by editing its contents in the Inspector.

3. **Add a Modular Building to Your Scene**  
   Right-click in the Hierarchy and select **Tower Generator > Modular Building**. This creates a GameObject with the `ModularBuilding` component.

4. **Generate Your Tower**  
   With the Modular Building GameObject selected, use the **Generate Tower** button in its inspector to assemble the tower based on your prefab library.

5. **Iterate Designs Quickly**  
   Use the **Regenerate** button to create variations swiftly without rebuilding the library.

This workflow enables fast creation and iteration of modular towers, streamlining level design and prototyping.

![Storyboard proof shot](images/storyboard-proof-shot.png)

---

Explore the usage instructions above to integrate Tower Generator into your city-building workflow. Quickly generate and regenerate towers to accelerate level design and experiment with architectural variations.

[View Tower Generator on the Unity Asset Store](https://assetstore.unity.com/publishers/36542)

---

For questions or assistance, please join the [support Discord](https://discord.com/invite/ajDgWPmSBS) or visit the [chrisburns.com.au](https://chrisburns.com.au).