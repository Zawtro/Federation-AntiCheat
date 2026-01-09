# Federation Authorization List

This repository is **for Roblox game developers only** who want to integrate **Federation Anticheat** into their experiences.  
Only approved games are authorized to run the script.

<img width="3732" height="571" alt="F A" src="https://github.com/user-attachments/assets/188647dd-103a-49ae-b0c9-8eff8f7e9350" />

---

## 📌 Purpose
The Federation Authorization List ensures that only authorized Roblox experiences can use Federation Anticheat.  
The script checks against this list before running.

---

## 🚫 Unauthorized Use
- Any Roblox game ID not included here is **not authorized**.  
- Attempts to bypass this restriction will result in denial of service.  
- Unauthorized use, tampering, or redistribution is strictly forbidden.

---

## 🚨 Asset Theft & Unauthorized Obtaining
> **Zero Tolerance Policy**  
> - Theft of assets, unauthorized obtaining of Federation scripts, or tampering with Federation Anticheat is strictly forbidden.  
> - This system exists to **protect our work** and ensure the anticheat functions as intended.  
> - Your responsibility as a developer is to protect your own assets — Federation Anticheat is not a shield for stolen content.  
> - Any attempt to steal, copy, or redistribute Federation Anticheat without authorization will result in permanent denial of service.  

---

## ❌ Editing, Forking, and Source Code Access
- Any form of **editing** this repository is prohibited.  
- **Forking** this repository is not allowed.  
- **Viewing or attempting to access the source code** of Federation Anticheat is strictly forbidden.  
- Violations of these rules will be treated as malicious activity and may result in permanent denial of service.  

---

## 🔧 How It Works
- Federation Anticheat checks the **Place ID** of the running game.  
- If the ID matches one in this list, the script runs normally.  
- If not, the script will refuse to execute.

### 🔑 How to Get Your Place ID. And Request Permission to Use
To request authorization, you’ll need your game’s **Place ID**. [Join our Discord Server](https://discord.gg/6mNT7SR8Pv)  
Run this line of code in Roblox Studio or your game console to retrieve it:
**RUN IN A COMMAND BAR**
```lua
print(game.PlaceId)
```
### OR
use game link
https://www.roblox.com/games/YourGameId
