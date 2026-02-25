---
title: "Simple Unity Hierarchy Folder"
layout: single
excerpt: "A utility for cleaning up Unity scene hierarchies using custom folder icons."
date: 2025-10-20
categories: 
  - Unity
  - Editor Tools
tags: 
  - Hierarchy
  - Tools
  - Workflow
header:
  teaser: /assets/images/portfolio/hierarchy-thumb.png
  overlay_image: /assets/images/portfolio/hierarchy-banner.jpg # Optional header image
  overlay_filter: 0.5

sidebar:
  - title: "Role"
    text: "Lead Developer"
  - title: "Tech"
    text: "Unity, C#"
  - title: "GitHub"
    text: "[View Repository](https://github.com/ProfessorAkram/SimpleUnityHierarchyFolder)"
---

## Summary
**SimpleUnityHierarchyFolder** enables the creation of dedicated folder objects in the Unity hierarchy for cleaner, more organized scenes. Hierarchy folders are empty GameObjects with transform access removed and represented with a folder icon, making it easy to visually structure large hierarchies. This system helps developers quickly understand scene organization at a glance and maintain a clean, navigable hierarchy.

## Technical Constraints & Goals
* **Maintain a clear hierarchy** for large scenes without affecting GameObject transforms.  
* **Visual Consistency:** Provide a system for scene organization that is informative (e.g., color-coded categories).  
* **Prefab Support:** Ensure compatibility with prefabs while retaining visual cues.  
* **Lightweight:** Easy installation via Unity Package Manager without breaking existing project structure.

## Design Pattern Rationale
* **Command Pattern**: Menu commands allow a consistent, centralized way to create folder objects via the Editor.
* **Decorator / Proxy**: Folder icon overlays and disabled transform access "decorate" standard GameObjects to behave like folders without altering runtime scene behavior.  
* **Modular Design**: Each folder acts independently, enabling flexible placement, color-coding, and prefab conversion.

## My Contribution
I developed this Unity package from scratch for educational purposes. This includes:  
* Implementing folder behavior and menu integration  
* Designing the color-coding system  
* Ensuring prefab compatibility  
* Documenting usage and recommended workflow

## External Assets & Libraries
* None; developed entirely in-house.  
* **License:** MIT License

---

### Resources
* [GitHub Repository](https://github.com/ProfessorAkram/SimpleUnityHierarchyFolder)  
* [Project Use Case](https://getcreativetoday.com/)