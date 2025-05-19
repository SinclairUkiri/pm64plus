# pm64plus

⚠️ **Legal Notice**  
This is a non-commercial fan project. You must provide your own legally obtained copy of *Paper Mario (N64)* to use this project.  
Nintendo owns all rights to *Paper Mario* and its characters. This port is provided for educational and preservation purposes only.

---

A **Paper Mario PC Port** based on decompilation of the original Nintendo 64 game, rebuilt for modern systems with added enhancements, improvements, and mod support!

---

## 📖 About

**pm64plus** is a personal project aiming to decompile, reconstruct, and enhance the original *Paper Mario (N64)* as a native PC port. The goal is to faithfully recreate the classic with optional quality‑of‑life features, visual tweaks, and technical improvements — all without relying on emulation.

---

## 🚀 Features (Planned)

- ✅ Native PC build (Windows; Linux planned later)  
- ✅ Optional HD textures and widescreen support  
- ✅ Quality‑of‑life improvements (faster dialogue, 60 FPS toggle, etc.)  
- ✅ Mod‑friendly asset and code structure  
- ✅ Optional audio and control enhancements  

---

## 🛠️ Build Instructions

> **Requirements**  
> - Python 3.10+  
> - Ninja  
> - CMake  
> - Rust (`cargo`)  
> - Visual Studio Build Tools (C++ Desktop components)  
> - A *legally obtained* `baserom.z64` (US version)

### 🔧 Setup

```bash
git clone https://github.com/SinclairUkiri/pm64plus.git
cd pm64plus
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
export PYTHONPATH=$PWD/tools
./configure
ninja -C build

