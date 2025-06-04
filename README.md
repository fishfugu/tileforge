# TileForge

**TileForge** is a cross-platform board designer project built in C++ with a focus on object-oriented design. It allows users to define and visualise custom boards for tile-based games — from grids to hexes and beyond.

This project is being developed collaboratively using [GitHub Codespaces](https://github.com/features/codespaces) for ease of setup and shared learning.

---

## 🚧 Status

This project is in early development. We're currently focused on building a simple local MVP with the following goals:

- Create a flexible board representation using OOP principles
- Add basic tile placement and piece management
- Output board state to the console
- Build with CMake for easy portability and future expansion

---

### 💻 Working with GitHub Codespaces

This project supports development directly in [GitHub Codespaces](https://github.com/features/codespaces) — no local setup required.

### Requirements (if not using Codespaces)
- C++17 or higher
- CMake 3.15+
- A compiler (GCC, Clang, or MSVC)

#### ✅ To get started:

1. Click the **Code** button at the top of the repository.
2. Select **"Open with Codespaces"** → **"+ New codespace"**.
3. A browser-based VS Code environment will launch automatically with all tools pre-installed.

---

#### 🛠 Build & Run

From the Codespaces environment:

* Press **`Ctrl+Shift+B`** (or **`⇧⌘B`** on Mac) to **build the project**.
* Open the Command Palette (`Ctrl+Shift+P` / `⇧⌘P`), type `Run Task`, and select **"Run TileForge"**.

You can also use the terminal:

```bash
cmake -S . -B build
cmake --build build
./build/tileforge
```

---

#### ⚙ What's Included in the Dev Container

The dev environment comes preloaded with:

* C++ compiler
* CMake
* VS Code extensions for C++ and CMake Tools

No need to install anything locally — ideal for quick collaboration and learning.

---

## 📜 License

This project is licensed under the [GNU General Public License v3.0](LICENSE).

---

## 👨‍👦 About

TileForge is a learning project created a learning oportunity, exploring object-oriented programming and collaborative game design tools. Contributions and feedback are welcome as the project evolves.

### 🤝 Contributing

We welcome contributions, whether you're here to help build the project, suggest features, or just learn alongside us!

#### To get started:

1. **Fork** the repository
2. **Create a branch** for your feature or fix
3. **Commit** your changes clearly
4. **Open a Pull Request** and describe your changes

If you're new to GitHub or open-source, feel free to ask questions. This project is designed to be beginner-friendly.

---

### 🗺 Roadmap

Here's a rough plan for the early stages of TileForge:

#### ✅ Phase 1: MVP (Console-based)

* [x] Set up development environment with C++ and CMake
* [ ] Define basic `Board`, `Tile`, and `Piece` classes
* [ ] Enable placing/removing pieces on a 2D grid
* [ ] Console output to visualise the board

#### 🚧 Phase 2: Features & Flexibility

* [ ] Add support for hex grids and custom shapes
* [ ] Implement basic board serialization (save/load)
* [ ] Add simple rule scripting (e.g. valid moves, adjacency)

#### 🔮 Phase 3: UI and Web Exploration

* [ ] Investigate UI libraries (ImGui, Qt)
* [ ] Begin exploring how this could evolve into a web app


---

### ✅ TODO

These are the next planned steps for the project. Contributions welcome!

#### 🧱 Core Functionality
- [ ] Define `Tile` class with basic properties (e.g. type, coordinates)
- [ ] Update `Board` class to store a grid of `Tile` objects
- [ ] Add ability to place and remove `Piece` objects
- [ ] Display board contents in the console visually (e.g. ASCII grid)

#### 🧪 Testing & Structure
- [ ] Create basic unit tests (maybe using `doctest` or `Catch2`)
- [ ] Improve CMake layout for modular compilation
- [ ] Add build/run/debug instructions to `tasks.json` or `launch.json`

#### 🌱 Stretch Goals
- [ ] Add support for different board layouts (e.g. hex, isometric)
- [ ] Save and load board state to file
- [ ] Begin investigating UI libraries for future visualisation
