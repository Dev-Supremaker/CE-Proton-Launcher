# CE-Proton-Launcher

A Bash script to automatically detect a running Proton game, locate and launch **Cheat Engine.exe** through `protonhax`, then monitor running Steam game processes to wait for their exit and clean up any leftover Cheat Engine or Proton processes.

---

## Dependencies

- **[Cheat Engine](https://cheatengine.org/)**

- **[`protonhax`](https://github.com/jcnils/protonhax)**

Ensure these are available on your system.

---

## Installation

1. Install **Cheat Engine** for Windows and ensure `Cheat Engine.exe` is accessible from your Linux filesystem (e.g., via Wine prefix or mounted directory).
2. Clone or download this script.
3. Make sure `protonhax` is installed and available in your system PATH.
4. Make the script executable:
   ```bash
   chmod +x CE-Proton-Launcher
