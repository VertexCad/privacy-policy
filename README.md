# Privacy Policy for Vertex CAD

**Effective Date:** May 20, 2024

Vertex CAD ("we", "us") respects your privacy. This policy outlines how information is handled in the Vertex CAD mobile application.

---

### 1. Information Collection & Privacy
* **Zero Personal Data:** We do not collect, transmit, store, or share any personal identifiable information (PII), user accounts, or device identifiers.
* **No Tracking or Analytics:** The app contains no third-party tracking, advertising, or telemetry SDKs.

---

### 2. File Access & Local Storage
* **Local Processing:** CAD files (STEP, IGES, Inventor, PDF) are parsed and rendered **100% locally on your device** by default.
* **Temporary Cache:** Opening files from other apps creates a temporary local copy in the app's cache (`cache/incoming`) that is automatically cleaned up.
* **On-Device Preferences:** App settings (theme, display options) are saved locally on your device (`localStorage`) and never transmitted off-device.
* **Printing & Sharing:** Exported drawings or print snapshots are handled locally by Android's native share and print services.

---

### 3. Optional Autodesk Cloud Conversion (APS)
For complex Autodesk Inventor models (`.ipt`, `.zip`), an optional cloud conversion feature is available:
* **Vertex Access Keys:** Access keys are kept strictly in temporary session memory while open and are never stored permanently or logged.
* **Explicit User Consent:** Selecting a file does **not** upload it. Files are sent to Autodesk Platform Services **only** when you check the consent box and click Upload.
* **Data Processing:** Uploaded files are converted by Autodesk under the [Autodesk Privacy Statement](https://www.autodesk.com/company/legal-notices-trademarks/privacy-statement). Converted models are temporary and no personal identity is attached.

---

### 4. Device Permissions
* **`INTERNET`:** Required for web engine asset loading and the optional Autodesk cloud conversion feature.
* **`READ_EXTERNAL_STORAGE` / `READ_MEDIA_IMAGES`:** Used solely to select and open CAD files or save exported drawings.

---

### 5. Contact Us
For questions regarding this policy, contact us at: **welding@sunsethb.com**
