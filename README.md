# GASP+ALS with Inventory Integration  
🚀 **REPLICATED & BLUEPRINT-ONLY** 🚀  
*(Fully Networked - No C++ Required!)*  

## About This Project  
This repository is a **fork** of PolygonHive's GASP+ALS, with additional **Inventory System functionality** integrated.  

- Looking for the **original GAS+ALS system**? Check out [PolygonHive’s GitHub](https://github.com/PolygonHive/GASP-ALS).  
- Want an **enhanced version** with inventory mechanics? You’re in the right place!  
- ⚡ **Fully replicated for multiplayer games** (supports networking).  
- 🛠 **Blueprint-Only**—No C++ required!  

## Features Added in This Fork  
✔ **Fully Integrated Inventory System**  
✔ **Supports Pickup & Item Management**  
✔ **Modular Structure for Easy Expansion**  
✔ **Overlay System Adjustments for Inventory Compatibility**  
✔ **Multiplayer-Compatible (Replication Ready!)**  
✔ **100% Blueprint-Based Implementation**  

### **🔧 Inventory System Overview**  
#### **📌 Character Inventory Updates**  
- `CBP_Character` now includes `BPI_Inventory`, enabling the `"Pickup"` function.  
- Inventory-related functionality can be found **inside the event graph** of `CBP_Character`.  
- All additional inventory mechanics are organized within the `"Inventory"` folder.  

#### **📌 Overlay System Adjustments**  
- Inside `"Overlay System" → "Overlays" → "DataAssets"`, the `"Pistol"` asset has been **modified**.  
- Some internal data was **wiped** to ensure compatibility with inventory mechanics.  
- **If reusing the Overlay System**, check these files to confirm integration.  

### **🛠 How The Inventory System Works**  
**Adding New Items:**  
1. Navigate to `Content → Inventory → DT_Inventory`.  
2. Add new items by modifying the **Data Table (`DT_Inventory`)**.  

**Placing Pickup Items in the Game:**  
1. Go to `Content → Inventory → Blueprints`.  
2. Locate `BP_Pickup` and place it in the level.  
3. Open the `"Details"` tab and set the **ID** to match an item from `DT_Inventory`.  

---

### ☕ **Support the Original Creator - PolygonHive** ☕  
The **GASP+ALS system** was originally developed by **PolygonHive**—if you love their work, consider buying them a coffee!  
They need the fuel to keep creating awesome tools for the Unreal Engine community.  

👉 **[Buy Me A Coffee](https://buymeacoffee.com/PolygonHive)**  

---

### 🚀 Future Updates  
- More documentation on Inventory System  
- Expanded functionality for modular game development  

Stay tuned for improvements! Let me know if you have suggestions!  
