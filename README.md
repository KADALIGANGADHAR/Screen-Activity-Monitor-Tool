# 🖥️ Screen Activity Monitor Tool

This tool takes automated screenshots of the desktop every 10 seconds using Python and `pyautogui`.

## 📌 Features

- Captures full-screen screenshots every 10 seconds
- Stores them in a local `screenshots/` folder

## 🚀 Setup Instructions

### 1. Update Kali Linux (Optional)
**```sudo apt update && sudo apt upgrade -y```**

<img width="1592" height="839" alt="kali-linux-2024 4-vmware-amd64-2025-07-10-19-14-21" src="https://github.com/user-attachments/assets/a811e0b5-89c9-4db8-b1ef-3db1bca6e481" />

### 2. Install Screenshot Tools (Optional)
**```sudo apt install flameshot kazam scrot -y```**

<img width="1592" height="839" alt="kali-linux-2024 4-vmware-amd64-2025-07-10-19-16-49" src="https://github.com/user-attachments/assets/fd5d691c-e7f7-4b52-9644-7a557badf178" />
<img width="1592" height="839" alt="kali-linux-2024 4-vmware-amd64-2025-07-10-19-16-55" src="https://github.com/user-attachments/assets/a0d37bba-73a3-4096-8314-274ccd1d35af" />
<img width="1592" height="839" alt="kali-linux-2024 4-vmware-amd64-2025-07-10-19-17-02" src="https://github.com/user-attachments/assets/0f8248fa-3307-4220-ab19-a8935ab0741e" />

### 3. Set Up Python Virtual Environment
***For command-line screenshots, ensure scrot is installed:***
<img width="1592" height="839" alt="kali-linux-2024 4-vmware-amd64-2025-07-10-19-19-12" src="https://github.com/user-attachments/assets/cec2e9be-2759-4fe4-9085-2e8736bf179b" />
<img width="1592" height="839" alt="kali-linux-2024 4-vmware-amd64-2025-07-10-19-19-23" src="https://github.com/user-attachments/assets/e0724955-5d86-4d34-8743-6abbeda5f74e" />
<img width="1592" height="839" alt="kali-linux-2024 4-vmware-amd64-2025-07-10-19-19-30" src="https://github.com/user-attachments/assets/850b7552-a6d5-494f-bc5c-1e613f439277" />



**```sudo apt install python3-venv -y```**

**```mkdir ~/screen_monitor```**

**```Python3 -m venv venv```**

**```source venv/bin/activate```**

<img width="1592" height="839" alt="kali-linux-2024 4-vmware-amd64-2025-07-10-19-26-21" src="https://github.com/user-attachments/assets/55af4ed0-eb44-416c-b322-ba1e667f3d79" />

### 4. Install Python Screenshot Libraries
**```pip install pyautogui pillow```**

<img width="1592" height="839" alt="kali-linux-2024 4-vmware-amd64-2025-07-10-19-28-39" src="https://github.com/user-attachments/assets/78b21b9e-4073-4d88-8f86-106496dabda3" />





