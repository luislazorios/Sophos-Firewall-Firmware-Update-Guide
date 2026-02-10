# 📋 Sophos Firewall: Firmware Update Guide

  
**Luis Lazo**
**Purpose:** Update Firewall firmware via Sophos Central for customer appliances *(NO afecta endpoints)*

---

## 🚀 Step-by-Step Instructions

1. **🔐 Login to Sophos Central**  
   Go to [central.sophos.com](https://central.sophos.com) → **My Products** > **Partner Portal**

2. **👥 Navigate to Customer**  
   **My Business** > **My Customers** > **Customers**
   
   ![customer](/doc/customers.png)
   
   Click desired customer *(it highlights)*
   

    ![launch](/doc/launch.png)
   

4. **🎯 Launch Customer Portal**  
   Click **Launch Customer** *(opens new window/tab)*

5. **🔥 Access Firewall**  
   **My Products** > **Firewall Management** > **Firewall**
   
   ![firewall](/doc/firewall.png)

   Click the Firewall → Opens info tab

   ![launch2](/doc/launc2.png)
   

7. **⚙️ Update Firmware**  
   Left panel: **BACKUP & FIRMWARE** > **Firmware**  

   ![firmware](/doc/firmware.png)
   
   Check current version → **Check for updates** → **Download & Install**

   ![install](/doc/install.png)  

---

## ✅ Pre-Update Checklist

| Item | Action |
|------|--------|
| **Backup** | Backup & Firmware > **Backup Now** |
| **HA Pair** | Check failover *(no primary update in HA)* |
| **Downtime** | 5-30 min reboot; notify off-hours |
| **Licenses** | Check expiry in Licensing |



**👤 Author:** Luis Lazo  

