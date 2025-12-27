# 🚀 Microsoft Intune MSI Application Deployment – Notepad++

## 📌 Project Description
This repository documents an **end-to-end MSI application deployment project** using **Microsoft Intune (Endpoint Manager)**.

The application deployed is **Notepad++**, a popular lightweight text/code editor.  
Ye project **modern endpoint management**, **silent installation**, aur **enterprise-level app deployment** ka practical demonstration hai.

🎯 **Ideal for**:
- Intune L1 / L2 Support
- Endpoint Administrator (Fresher)
- Modern Workplace / IT Support Roles

---

## 🎯 Project Objectives
- MSI-based application deployment using Microsoft Intune  
- Silent installation without user interaction  
- Proper install, uninstall & detection rules  
- Application assignment to devices/users  
- Deployment monitoring & troubleshooting  
- Real-world Intune hands-on experience  

---

## 🛠️ Tools & Technologies
- **Microsoft Intune (Endpoint Manager Admin Center)**
- **Windows 10 / Windows 11**
- **Notepad++ MSI Installer**
- **Azure Active Directory**
- **Windows PowerShell** (basic verification)

---

## ❓ Why Notepad++?
Notepad++ is selected because:
- Official MSI installer available  
- Supports silent installation  
- Lightweight & fast deployment  
- Commonly used in IT environments  

---

## 🧱 Deployment Architecture
1. Admin uploads MSI app to Intune  
2. Intune processes app metadata  
3. App is assigned to target Azure AD group  
4. Managed devices sync with Intune  
5. Silent installation happens in background  
6. Installation status is reported back to Intune portal  

---

## ⚙️ Step-by-Step Implementation

### 1️⃣ Download MSI Installer
- Download official **Notepad++ (.msi)** installer  
- Prefer **x64 version**  
- Verify file integrity from official source  

---

⭐ *If you found this project helpful, don’t forget to star the repository!
### 2️⃣ Add Application in Intune
**Path:**
-----

Endpoint Manager Admin Center
→ Apps
→ Windows
→ Add
→ Windows app (MSI)

Upload the **Notepad++ .msi** file.

---

### 3️⃣ App Information
- **Name:** Notepad++  
- **Publisher:** Notepad++ Team  
- **Category:** Productivity / Utilities  

**Description:**
> Notepad++ MSI application deployed using Microsoft Intune for centralized and silent installation on managed Windows devices.

---

### 4️⃣ Program Configuration
(Intune auto-detects MSI properties)
- **Install command:** Auto-detected  
- **Uninstall command:** Auto-detected  
- **Install behavior:** System  
- **Restart behavior:** No restart  

---

### 5️⃣ Requirements
- **Operating System:** Windows 10 (1909+) / Windows 11  
- **Architecture:** 64-bit  
- **Disk Space:** Minimal  

---

### 6️⃣ Detection Rule
- **MSI Product Code** (Auto-detected by Intune)  
- Ensures accurate installation detection  
- Prevents duplicate installations  

---

### 7️⃣ Assignment
- Assigned to **All Devices** or **Test Device Group**  
- **Deployment type:** Required  

---

## 📊 Monitoring & Verification

### From Intune Portal:


Apps → Notepad++ → Device Install Status

**Possible statuses:**
- Installed  
- Pending  
- Failed  

### On Client Device:
- Notepad++ visible in **Start Menu**  
- Application launches successfully  
- Listed in **Programs & Features**  

---

## 🔐 Security Considerations
- Trusted MSI source  
- Silent install reduces user interaction risk  
- Centralized control & quick uninstall  
- Improves enterprise security posture  

---

## 📚 Learning Outcomes
- Practical MSI deployment experience  
- Understanding Intune application lifecycle  
- Real-world troubleshooting exposure  
- Enterprise endpoint management fundamentals  

---

## ✅ Conclusion
This project demonstrates how **Microsoft Intune** can efficiently deploy **MSI-based applications** like **Notepad++** in a secure, scalable, and automated manner.

It reflects **real-world enterprise deployment scenarios** and strengthens **endpoint management fundamentals**, especially for **Intune L1/L2 roles**.

---

## 👤 Author
**Huzaifa Shamim**  
🎓 MCA Student | Endpoint Management Learner  

🔗 **GitHub:** https://github.com/HShamim30/Microsoft-Intune-MSI-Application-Deployment  
🔗 **LinkedIn:** https://www.linkedin.com/in/huzaifa-shamim-ahmad-59987539a/
