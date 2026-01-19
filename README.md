# Nextcloud Passwords WebExtension

<div align="center">

**Autofill, Anywhere**

[![Browser](https://img.shields.io/badge/Browser-Chrome%20%7C%20Firefox-orange?style=for-the-badge&logo=google-chrome)]()
[![Nextcloud](https://img.shields.io/badge/Ecosystem-Nextcloud-blue?style=for-the-badge&logo=nextcloud)]()

*The official browser extension for the Nextcloud Passwords app.*

</div>

---

## 📖 Overview
This browser extension connects your browser to your self-hosted Nextcloud Passwords instance. It allows you to autofill credentials, save new passwords, and generate secure passwords directly from your toolbar.

## ✨ Features
*   **Autofill:** Detects login forms and fills them with a click.
*   **Save:** Prompts to save new credentials after a successful login.
*   **Generate:** Create strong, customizable passwords on the fly.
*   **Search:** Quick search for any credential in your vault.

---

## 🗺️ Roadmap & Todo

### Phase 1: Core Functionality
- [ ] **Connection:** Implement the secure handshake with the Nextcloud API.
- [ ] **Popup UI:** Build the main popup interface (Search + List).
- [ ] **Background Script:** Handle state management and API calls.

### Phase 2: Page Interaction
- [ ] **Content Script:** Inject icons into login fields.
- [ ] **Form Detection:** robustly identify username and password fields (even on tricky sites).
- [ ] **Autofill:** Securely inject values into the DOM.

### Phase 3: Advanced Features
- [ ] **Biometrics:** Support Windows Hello / TouchID for unlocking the vault.
- [ ] **Multiple Accounts:** Support switching between different Nextcloud user accounts.
- [ ] **TOTP:** Auto-fill 2FA codes if stored in the entry.

### Phase 4: Release
- [ ] **Firefox:** Submit to Mozilla Add-ons (AMO).
- [ ] **Chrome:** Submit to Chrome Web Store.
