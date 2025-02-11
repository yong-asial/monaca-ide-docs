# Build Environment Settings - User Manual

This guide provides a detailed explanation of the **Build Environment Settings** available in **Monaca Cloud IDE**.

---

## 1. iOS Build Environment Settings

### Fields Explanation:

- **Platform:**  
  - Displays the iOS platform version used for building the app.

- **Xcode Version:**  
  - Select the Xcode version used for compiling the iOS application.
  - Options include **Xcode 13** and **Xcode 14.2.0**.

- **Build Flag:**  
  - Specify additional build flags for debugging and release builds.
  - The `-quiet` flag suppresses unnecessary build output.

- **dSYM Download:**  
  - If enabled, **Debug Symbols (dSYM)** files will be available for download.
  - These files help in **crash debugging and symbolication** of error reports.

---

## 2. Android Build Environment Settings

### Fields Explanation:

- **Platform:**  
  - Select the Android version to build the app.
  - Options include **Android 10.1.1, Android 10.1.2, and Android 11.0.0**.

- **Package Type:**  
  - Choose the output package format for the Android build:
    - **APK:** A standard Android application package.
    - **App Bundle:** A more optimized package format recommended for **Google Play Store distribution**.

---

## 3. Other Build Options

### Fields Explanation:

- **npm install command line options:**  
  - Enables additional options for managing Node.js package installations.

  - **`--production:`**  
    - If enabled, only production dependencies are installed, **excluding development dependencies**.

  - **`--legacy-peer-deps:`**  
    - If enabled, **legacy peer dependency resolution** is used to prevent package conflicts.

- **No devDependencies:**  
  - If enabled, development dependencies will be completely excluded from the build process.

---

## 4. Saving Changes

Once you have configured the settings, click **Save** to apply the changes.

---

This guide explains all fields in the **Build Environment Settings** section of **Monaca Cloud IDE**.
