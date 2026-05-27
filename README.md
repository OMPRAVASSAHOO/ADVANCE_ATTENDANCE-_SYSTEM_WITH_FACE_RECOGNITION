# Aegis - Serverless Face Attendance System

A premium, serverless face-recognition attendance system that runs **100% in the browser** on any mobile device (Android/iOS) or laptop without needing servers, packages, or terminal commands.

## 🌟 Key Features
* **Browser-Based Neural Engine**: Uses `face-api.js` (TensorFlow.js) to compute face detections and face embeddings directly on your mobile device's processor.
* **IndexedDB Local Storage**: Stores your student face prints, daily attendance logs, and cropped photos securely inside the browser's database on your device.
* **Cryptographic Passcode Protection**: Protected by a passcode setup screen. Passcodes are hashed locally using browser-native **SHA-256** encryption and saved strictly in your device's private browser partition. The plain-text password is **never** stored in the source code or uploaded to GitHub.
* **Premium Client-Side Excel Exports**: Generates styled multi-sheet Excel reports with green/red status highlighting and automated defaulter "Red Lists" (<75% attendance) directly on your device using `ExcelJS`.
* **Backup & Restore**: Easily download a `.json` backup file of all your data (faces, logs, photos) and restore it on any device to avoid data loss.

---

## 🚀 How to Set Up on Your GitHub Account (Free & Secure)

To access the app on your phone, you can host these files on GitHub Pages for free. This takes less than 2 minutes and requires no technical experience.

### Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com/) and log in (or create a free account).
2. Click the green **New** button (or **Create repository**) on the dashboard.
3. Name your repository (e.g., `attendance`).
4. Select **Public** (required for free GitHub Pages).
5. Leave everything else unchecked and click **Create repository**.

### Step 2: Upload the Files
1. On your new repository page, click the link that says: **"uploading an existing file"**.
2. Open your computer's file explorer and navigate to: `D:\advance attendance serverless`
3. Select and drag all four files:
   - `index.html`
   - `style.css`
   - `app.js`
   - `README.md`
4. Drop them into the GitHub file upload box.
5. Wait for the files to finish uploading, then click the green **Commit changes** button at the bottom of the page.

### Step 3: Enable GitHub Pages
1. Go to the **Settings** tab (gear icon) at the top of your GitHub repository.
2. In the left sidebar under the "Code and automation" section, click on **Pages**.
3. Under the "Build and deployment" section, find the **Branch** dropdown.
4. Click the dropdown (which currently says "None") and select **main** (or `master`).
5. Click **Save**.
6. Wait about 30 seconds to 1 minute, and refresh the page. A box will appear at the top showing your live URL, which looks like this:
   `https://<your-username>.github.io/<repository-name>/`

---

## 📱 Accessing the App on Your Phone
1. Open Chrome/Safari on your mobile phone.
2. Enter your live GitHub Pages URL (e.g. `https://<your-username>.github.io/attendance/`).
3. **First-Time Setup**: Since no passcode is stored yet, the app will show a **"CREATE PASSCODE"** screen. Type a strong passcode of your choice and click **Save & Open App**.
4. The browser will prompt for **Camera Access**. Click **Allow**.
5. Select or type a class, start the camera, and begin taking attendance!

*Tip: Add the page to your phone's Home Screen (open mobile Chrome settings ➡️ "Add to Home screen") to use it like a regular mobile app!*
