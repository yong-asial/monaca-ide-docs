# Capacitor iOS Configuration - User Manual

This guide provides a detailed explanation of the **Capacitor iOS Configuration** settings available in **Monaca Cloud IDE**.

---

## 1. Application Information

The **Application Information** section allows you to configure essential details for your iOS app.

### Fields Explanation:

- **Application Name (Required):**  
  - The name of your application that will appear on the device's home screen.

- **App ID (Required):**  
  - A unique identifier for your app (e.g., `jp.co.asial.monaca`).  
  - This must follow the **reverse domain name format**.

- **Version Number (Required):**  
  - The version number of your app (e.g., `1.0.0`).  
  - This follows **semantic versioning** (`major.minor.patch`).

- **Bundle Version Number:**  
  - A numeric value that increases with each app release.  
  - If left blank, the system will automatically assign a version number.

- **Localizations:**  
  - Specifies which languages your app supports.  
  - Select one or more from **English, French, German, Italian, Spanish, Japanese, Korean, Chinese (simplified), and Chinese (traditional)**.

---

## 2. Icons & Splash Screen Configuration

The **Icons & Splash Screen** section allows you to upload and manage your app’s icons and splash screen.

### Fields Explanation:

- **App Icon:**  
  - Upload an **App Icon** in **PNG or SVG format**.  
  - Recommended size: **1024 × 1024 px**.
  - Click **Change** to update the icon.

- **Splash Screen:**  
  - Upload a **Splash Screen Image** that appears when launching the app.  
  - The recommended resolution is **2732 × 2732 px**.
  - Click **Change** to update the splash screen.

- **Background Color:**  
  - Set a **background color** for the **App Icon** and **Splash Screen**.
  - Choose **"None"** if no background is required.

---

## 3. Target Device Family

The **Target Device Family** section lets you choose the devices your app will support.

### Options:
- **iPhone** - The app will be available for iPhone devices.
- **iPad** - The app will be available for iPad devices.

---

## 4. Miscellaneous Settings

The **Misc** section provides additional configurations for your app.

### Fields Explanation:

- **Screen Orientation:**  
  - Defines how the app is displayed on the device.
  - Options:
    - **All:** Supports both landscape and portrait orientations.
    - **Landscape:** Forces the app to run in landscape mode.
    - **Portrait:** Forces the app to run in portrait mode.

---

## 5. Saving Changes

Once you have configured the settings, click **Save** to apply the changes. Some changes require **rebuilding** the app for them to take effect.

---

This guide explains all fields in the **Capacitor iOS Configuration** section of **Monaca Cloud IDE**.
