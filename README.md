🚀 Gunball OS - The Modular Workstation Kernel
Welcome to the Gunball OS repository. This is a high-performance, modular 64-bit kernel designed for developers who want a system that adapts to their needs.
🧭 Philosophy & Vision
The core philosophy of Gunball OS is "Absolute Modularity." We believe an Operating System should be a blank canvas. Whether you want to build a secure server, a portable hacking station, or a low-level development environment, Gunball OS provides the "building blocks" to make it happen.
User-Centric Control: You decide which modules are loaded.
Hardware Empowerment: Direct communication with CPU/GPU.
Simplicity over Bloat: No unnecessary background processes.
⌨️ Command Reference (Official CLI)
The following block is treated as raw source code to prevent any translation and ensure technical accuracy:
/* * GUNBALL OS - OFFICIAL COMMAND LIST v2.9
 * These commands are hardcoded in the C Kernel. 
 * DO NOT TRANSLATE.
 */

// --- Connectivity ---
wifi scan                       // Searches for nearby wireless networks
wifi connect [ssid] [pass]       // Joins a Wi-Fi network using WPA2
bt-on / bt-scan                 // Enables Bluetooth and discovers devices
bt-connect [id]                 // Pairs with Headphones, Mice, or Phones

// --- Security & Auth ---
set-key [pass]                  // Initializes the 256-bit AES master key
encrypt [file]                  // Secures a file with AES-256 encryption
user-add [name] [pass]          // Creates a permanent user account on HD
login [name] [pass]             // Authenticates and loads user permissions
whoami                          // Displays the current session user

// --- Media & Terminal ---
play [file.mp3]                 // Starts background audio playback
view [file.mp4]                 // Renders video directly to terminal
stop                            // Terminates all active media streams
clear                           // Wipes the terminal screen buffer

// --- System & Power ---
sh [file.gsh]                   // Executes automated Shell scripts
dmesg                           // Accesses the Kernel error logs
battery                         // View battery health and CPU temp
power-save / perf-mode          // Toggles Eco vs Max Performance
sleep                           // Enters S3 Suspend mode (RAM)
date / uptime                   // View RTC time and session duration
keymap set abnt2                // Switches keyboard to Brazilian standard

🛠️ Evolution Path
v1.0: 125 lines (Basic Boot)
v2.0: 1,000 lines (Multitasking)
v2.9/3.0: 3,000+ lines (Secure Workstation)
Gunball OS: Be what you want to be.
