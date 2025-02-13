# Build Environment Settings

You can set the environment settings for building applications. The settings are project-specific.

1. Open the **Build Environment Settings** page:  
   - Click the **Monaca** icon in the **Activity Bar**.  
   - Under the **"Build"** section, select **Build Environment Settings**.

2. The page will appear as shown below. You can then start your configuration.

3. After finishing the configuration, click **"Save"**.

  ![img](img/build-env-setting/build-env-setting.png)

## iOS

- **Platform:**  
  - Displays the iOS platform version used for building the app.

- **Xcode Version:**  
  - Select the Xcode version used for compiling the iOS application.

- **Build Flag:**  
  - Specify additional build flags for debugging and release builds.
  - The `-quiet` flag suppresses unnecessary build output.

- **dSYM Download:**  
  - If enabled, **Debug Symbols (dSYM)** files will be available for download.
  - These files help in **crash debugging and symbolication** of error reports.

---

## Android

- **Platform:**  
  - Select the Android version to build the app.

- **Package Type:**  
  - Choose the output package format for the Android build:
    - **APK:** A standard Android application package.
    - **App Bundle:** A more optimized package format recommended for **Google Play Store distribution**.

---

## Other Build Options

- **npm install command line options:**  
  - Enables additional options for managing Node.js package installations.

  - **`--production:`**  
    - If enabled, only production dependencies are installed, **excluding development dependencies**.

  - **`--legacy-peer-deps:`**  
    - If enabled, **legacy peer dependency resolution** is used to prevent package conflicts.

- **No devDependencies:**  
  - If enabled, development dependencies will be completely excluded from the build process.

---

## Notes

- This page is only for Cordova projects.
- Some settings may vary depending on the Cordova version.
