# ⚔️ Territory Wars

**Territory Wars** is an engaging, 2D grid-based arcade game inspired by classics like *PacXon*. Built entirely in C++, this project demonstrates strong Object-Oriented Programming (OOP) principles, custom game logic, and state management, making it a robust showcase of software development practices.

The objective is to claim territory on the map while strategically outmaneuvering various types of AI enemies designed to hunt you down or destroy your progress.

## ✨ Key Features

* **Advanced Enemy AI:** Features multiple enemy archetypes with unique behaviors, utilizing polymorphism:
  * 👾 *Default Enemy:* Standard patrolling logic.
  * 🎯 *Hunter Enemy:* Actively tracks and pursues the player.
  * 💥 *Destroyer Enemy:* Capable of breaking through defenses or claimed territory.
* **Save & Load System:** Custom file parsing (`FileManager`) allows players to save their progress (`gameSave.txt`) and load custom map configurations (`levels.txt`, `map.txt`).
* **Custom Game Engine Mechanics:** Built from the ground up with custom modules for Keyboard Input, Animations, Window Management, and Entity handling.
* **Interactive UI:** Fully functional menus, clickable buttons, and dynamic text boxes using custom fonts (`DIGIB.TTF`).

## 🛠️ Tech Stack & Architecture

* **Language:** C++
* **Graphics Library:** SFML
* **Architecture:** Object-Oriented Design (OOD) with strict separation of concerns (Logic, UI, Entity Management, File I/O).
