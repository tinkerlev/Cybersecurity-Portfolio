# Screenshots and Videos Documentation

This folder contains visual evidence (screenshots and videos) collected during the testing of XSS vulnerabilities on the **Statuspage** platform. Each file provides a detailed view of the vulnerabilities and their execution.

---

## 📸 Screenshots

### 1. `XSS_Alert_Activate_Page_Select_Plan_Button.png`
- **Description:** Demonstrates an XSS vulnerability triggered via the "Select Plan" button on the **Activate Page**.
- **Payload Used:**
  ```html
  <span class="css-178ag60" onclick="alert('XSS')">Select plan</span>
  ```
- **Outcome:** A JavaScript alert (`XSS`) was successfully executed.

---

### 2. `XSS_Alert_Incidents_Page_Root_ID.png`
- **Description:** Shows an XSS payload injected into the `root` ID element on the **Incidents Page**.
- **Payload Used:**
  ```html
  <img src=x onerror=alert('XSS')>
  ```
- **Outcome:** The payload executed and displayed the alert box upon page load.

---

### 3. `XSS_Alert_Popup.png`
- **Description:** General example of an XSS alert box triggered during testing.
- **Outcome:** Confirms successful script execution.

---

### 4. `XSS_Customization_Page_and_AboutThePage.png`
- **Description:** Highlights an XSS vulnerability in the **Customization Page**. The payload was injected into the "About the Page" text field.
- **Payload Used:**
  ```html
  <img src=x onerror=alert('XSS')>
  ```
- **Outcome:** The payload executed when saving the page customizations.

---

### 5. `XSS_Plan_Selection_Select_Plan_Button.png`
- **Description:** Demonstrates an XSS vulnerability triggered via the "Select Plan" button on the **Plan Selection Page**.
- **Payload Used:**
  ```html
  <button onclick="alert('XSS via button')">Select Plan</button>
  ```
- **Outcome:** The script executed when interacting with the button.

---

## 🎥 Videos

### 1. `Video1.mp4`
- **Description:** Captures the full interaction and exploitation of the XSS vulnerability on the **Customization Page**.
- **Highlights:**
  - Shows injection of payload.
  - Demonstrates the alert box triggered upon saving changes.

---

### 2. `Video2.mp4`
- **Description:** Demonstrates the XSS payload in action on the **Incidents Page**.
- **Highlights:**
  - Shows payload injection and execution.

---

## ⚠️ Ethical Disclaimer
All screenshots and videos were captured as part of an **ethical security assessment** conducted with prior approval. These materials are shared for educational purposes only and must not be used in any unauthorized or malicious activities.
