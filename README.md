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

## 🛠 Development Setup

This project is Codespaces-ready.

### Requirements (if not using Codespaces)
- C++17 or higher
- CMake 3.15+
- A compiler (GCC, Clang, or MSVC)

### Running in Codespaces
Open the repository in GitHub Codespaces — the environment will configure automatically using the provided dev container.

---

## 📜 License

This project is licensed under the [GNU General Public License v3.0](LICENSE).

---

## 👨‍👦 About

TileForge is a learning project created a learning oportunity, exploring object-oriented programming and collaborative game design tools. Contributions and feedback are welcome as the project evolves.

Great! Below are clean, drop-in **`Contributing`** and **`Roadmap`** sections you can append to the existing `README.md` on [tileforge](https://github.com/fishfugu/tileforge):

---

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
