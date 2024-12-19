# 🐧 NixOS Configuration Repository

This repository contains my NixOS configuration files for setting up a personalized, efficient, and modern desktop environment.

---

## 📂 Repository Structure  
```plaintext
.
├── configuration.nix       # Main configuration file
├── hardware-configuration.nix # Auto-generated hardware settings
├── README.md               # You are here!
```

---

## 💾 Installation  

### 1️⃣ Clone this repository:  
```bash
git clone https://github.com/jabaldoo/NixOS-Configurations.git
cd NixOS-Configurations
```

### 2️⃣ Link configuration files:  
```bash
sudo cp configuration.nix /etc/nixos/
sudo cp hardware-configuration.nix /etc/nixos/
```

### 3️⃣ Apply the configuration:  
```bash
sudo nixos-rebuild switch
```

---

## 📦 Installed Packages  
A list of key packages included in this configuration:  

- **Development**:  
  `vscode`, `arduino-ide`, `obsidian`  

- **Gaming**:  
  `steam`, `discord`  

- **Utilities**:  
  `flatpak`, `github-cli`, `github-desktop`, `git`  

- **Other Tools**:  
  `neofetch`, `latte-dock`, `obs-studio`  

---

> **Note**: This configuration is tailored to my ThinkPad system. Hardware-specific settings may need adjustment for other devices.
