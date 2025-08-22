# Automated-Client-Intake-System

## 📌 Overview
This project automates the process of collecting and managing Google Form responses using **Make.com**.  
It connects Google Forms with Google Sheets to streamline lead collection, budget tracking, and client communication.

- **Trigger:** New Google Form response  
- **Logic:** Check if the respondent already exists in Google Sheets (via email)  
- **Action:**  
  - Add a new row if no match is found  
  - Update the existing row if the email already exists  
- **Extra:** Automatically extracts website URLs from responses using regex

---

## ⚙️ Tech Stack
- **Make.com** (formerly Integromat)  
- **Google Forms**  
- **Google Sheets**  
- **Regex Parser**

---

## 🚀 Features
- Real-time synchronization between Forms and Sheets  
- Smart deduplication (avoids duplicate leads by checking email)  
- URL extraction from form responses  
- Automatic status columns (e.g., *Contacted*, *Rejected*, *Initially Contacted*)  
- Timestamp logging for first contact  

---

## 📂 Files
- `Integration Google Forms.blueprint.json` → Importable Make.com scenario blueprint

---

## 🔧 Usage
1. Open [Make.com](https://www.make.com/)  
2. Create a new scenario  
3. Import the provided `blueprint.json` file  
4. Connect your Google account (Forms + Sheets)  
5. Update the `Spreadsheet ID`, `Sheet Name`, and `Form ID` to match your setup  
6. Activate the scenario  

---

## 🏆 Benefits
- Saves time on manual copy-pasting from Google Forms to Sheets  
- Ensures clean, deduplicated client data  
- Perfect for **freelancers, small businesses, or agencies** managing client intake  

---

## 📜 License
MIT License
