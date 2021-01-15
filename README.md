# pc-setup

## I. Manual Prerequisites

- OS: Windows 10
- Username: Vinnie
- Drives:
  - C: Local Disk (with Windows)
  - D: WD Blue
  - E: EVO SSD
- Installed:
  - Chrome
  - cURL

## II. Result

### A. Installation

#### 1. Drivers / Controllers

- Dragon Center (MSI motherboard)
- GeForce Experience (GPU)
- iCUE (LED controller)
- Nvidia Broadcast
- Brother Utilities (printer)

#### 2. General Apps

- Adobe Acrobat Reader
- Audacity
- Firefox
- Notepad++
- VLC

#### 3. Software Development

- Java 8
- Git
- NodeJS
- Python
- WinSCP
- IntelliJ

#### 4. Games

- Battle.net
- Discord
- League of Legends
- Minecraft + Optifine
- Minion
- Steam

### B. Setup

#### 1. Symbolic Links

```
mklink /D C:\Users\Vinnie\AppData\Roaming\.minecraft E:\symlinks\.minecraft
mklink /D C:\Users\Vinnie\AppData\LocalLow\VRChat E:\symlinks\VRChat
mklink /D C:\Users\Vinnie\AppData\Local\Google E:\symlinks\Google
```
