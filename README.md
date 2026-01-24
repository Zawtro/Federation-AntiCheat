# Federation Authorization List

This repository is for Roblox game developers who want to integrate **Federation Anticheat** into their experiences.  
Only approved games are authorized to run the script.

<img width="3732" height="571" alt="F A" src="https://github.com/user-attachments/assets/188647dd-103a-49ae-b0c9-8eff8f7e9350" />

---

## 📌 Purpose
The Federation Authorization List ensures that Federation Anticheat is used only in approved Roblox experiences.  
This keeps the system secure and reliable for everyone.

---

## 🚫 Unauthorized Use
- Games not listed here are not authorized to run Federation Anticheat.  
- If a game ID isn’t on the list, the script will refuse to execute.  
- Please don’t attempt to bypass or redistribute the system.

---

## 🚨 Asset Protection
> **Zero Tolerance Policy**  
> - Federation Anticheat is designed to safeguard fair play and protect developer work.  
> - Copying, tampering, or redistributing the scripts is strictly forbidden.  
> - Unauthorized use may result in permanent denial of service.  
> - Federation Anticheat supports your projects, but it is not intended to protect stolen content.  

---

## ❌ Editing, Forking, and Source Code Access
- Editing or forking this repository is not allowed.  
- Accessing or attempting to view the source code is restricted.  
- Violations will be treated as malicious activity and may result in denial of service.  

---

## 🔧 How It Works
- Federation Anticheat checks the **Place ID** of the running game.  
- If the ID matches one in this list, the script runs normally.  
- If not, the script will stop execution.

---

### 🔑 How to Get Your Place ID & Request Authorization
To request authorization, you’ll need your game’s **Place ID**. [Join our Discord Server](https://discord.gg/6mNT7SR8Pv)  

Run this line of code in Roblox Studio or your game console:
```lua
print(game.PlaceId)
