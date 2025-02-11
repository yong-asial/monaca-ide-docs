# iOS App Setting

There are 2 ways to configure your iOS apps:

- Configure via the IDE
- Configure via configuration files directly

## Configure via the IDE

The iOS App Settings page allows to set several commonly used parameter in iOS app. Please follow the following instruction in order to access the iOS App Setting page in the IDE:

1. Open the **iOS App Settings** page:  
   - Click the **Monaca** icon in the **Activity Bar**.  
   - Under the **"App Settings"** section, select **iOS App Settings**.

2. The page will appear as shown below. You can then start your configuration.

3. After finishing the configuration, click **"Save"**.

    ![img](img/capacitor-ios-app-setting/capacitor-ios-app-setting.png)

### Configurable Parameters

In the iOS App Settings page, you can configure the parameters such as application information, icons, splash files, permissions and additional features. The following are the list of parameters can be configured via the page:

#### Application Information

The **Application Information** section allows you to configure essential details for your iOS app.

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

#### Icons & Splash Screen Configuration

The **Icons & Splash Screen** section allows you to upload and manage your app’s icons and splash screen.

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

#### Target Device Family

The **Target Device Family** section lets you choose the devices your app will support.

---

#### Miscellaneous Settings

The **Misc** section provides additional configurations for your app.

- **Screen Orientation:**  
  - Defines how the app is displayed on the device.
  - Options:
    - **All:** Supports both landscape and portrait orientations.
    - **Landscape:** Forces the app to run in landscape mode.
    - **Portrait:** Forces the app to run in portrait mode.

---

## Configure via configuration files

All the configuration parameters of an iOS app are stored in the files as follows:

- [Capacitor Config](https://capacitorjs.com/docs/config#example)
- [Trapeze Config](https://trapeze.dev/docs/Frameworks/capacitor)

---

## Notes

- Some settings apply to both Android and iOS.
