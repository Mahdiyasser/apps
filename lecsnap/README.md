# LecSnap 📸
**The Ultimate Student Companion for Organized, Distraction-Free Studying.**

LecSnap was created to solve a common student struggle: a system gallery cluttered with thousands of unorganized lecture photos mixed with personal memories. It provides a dedicated, professional environment to capture, organize, and review your studies with zero distractions.

---

## 🌟 Key Features

### 📂 Pro Organization
- **Subject-Based Folders**: Group your lectures under subjects (Math, Physics, Bio, etc.).
- **HSV Color Coding**: Personalize each subject using a professional HSV Color Wheel or quick presets. The entire app's theme adapts to the subject you're currently studying.
- **Smart Reordering**: Arrange your subjects and lectures easily. Use manual number entry with **Circular Shift Logic**—if you move Lecture #5 to #3, the others slide down automatically.
- **Manual Sort Mode**: Use dedicated Up/Down arrows to manually reorder subjects, lectures, and photos exactly how you want them.

### 🖼️ Intelligent Photo Gallery
- **Dedicated Zoom Mode**: A rock-solid, clamped pinch-to-zoom engine. Inspect every detail of a board without ever "panning into the void."
- **Immersive Study**: The phone's status bar is automatically hidden while viewing photos to keep you focused on the content, not the time.
- **Physical Rotation**: Rotating a photo rewrites the actual file on your disk, ensuring it looks correct in thumbnails, shared messages, and other apps.
- **In-Viewer Notes**: Add detailed notes to any photo with an editor that stays perfectly above your keyboard.
- **Save to Gallery**: Export any study photo directly to your phone's public gallery (Pictures/LecSnap) with one tap.

### 🚀 Bulk & Multi-Select Power
- **Selection Mode**: Long-press any photo to enter Multi-Select mode.
- **Bulk Share**: Select multiple photos to share them as a single bundle via WhatsApp, Telegram, or Email.
- **Bulk Delete**: Clean up your lectures by deleting multiple selected photos in one go.
- **Instant Sharing**: Share an entire lecture's worth of photos with auto-generated labels in seconds.

### 🛡️ Data & Storage Safety
- **Full Backup (Export/Import)**: Export your entire app data (hierarchy + images) into a single `.zip` file. Restore it on any device at any time.
- **Storage Monitoring**: Real-time free space tracking. The app warns you if you have less than **768MB** left to prevent data loss.
- **Safe Updates**: Your data is protected by managed database migrations. Updating the app will never delete your studies.
- **Privacy First**: No cloud backups or data tracking. Everything is stored locally on your device.

### 📸 High-Speed Capture
- **Built-in Camera**: Capture photos directly into the correct lecture.
- **Live Thumbnails**: See a strip of recently captured photos without leaving the camera screen.
- **Multi-Import**: Import multiple existing photos from your gallery at once.

---

## 🚀 How It Works
1. **Create a Subject**: Give it a name and a distinct color.
2. **Add a Lecture**: Set the lecture number, date, and time.
3. **Snap or Import**: Use the built-in camera to take photos or import them from your device.
4. **Study & Review**: Open the viewer, toggle Zoom Mode for details, and add notes to important points.
5. **Share & Backup**: Share selections with classmates or export a `.zip` backup to keep your data safe.

---

## 👨‍💻 Developed By
**Mahdi Yasser**  
*Full-Stack Web Developer & Android Developer*

I built LecSnap to help students take control of their learning materials with a fast, responsive, and reliable tool.

### 🔗 Contact & Socials
- **Website**: [mahdiyasser.com](https://mahdiyasser.com)
- **GitHub**: [@Mahdiyasser](https://github.com/Mahdiyasser)
- **Instagram**: [@mahdiyasser1](https://instagram.com/mahdiyasser1)
- **Facebook**: [@mahdy.elsmak.1](https://facebook.com/mahdy.elsmak.1)
- **WhatsApp**: [+201013297922](https://wa.me/201013297922)
- **Email**: [mahdiyasser526@gmail.com](mailto:mahdiyasser526@gmail.com)

---

## 🛠️ Technical Stack
- **Language**: Kotlin
- **UI**: Jetpack Compose (Modern Declarative UI)
- **Database**: Room (SQLite) with managed migrations
- **Camera**: CameraX API
- **Image Processing**: Efficient Bitmap caching and physical Matrix rotation
- **Format**: GSON for metadata and ZIP for backups

---

## 📖 Step-by-Step User Guide

### 1. Creating Your First Subject
- **Step 1**: On the home screen ("المواد"), tap the large **+** button at the bottom.
- **Step 2**: Enter the name of your subject (e.g., "Organic Chemistry").
- **Step 3**: Choose a color. You can tap one of the 8 presets or tap the **Edit (Pencil)** icon to open the **HSV Color Wheel** for a custom shade.
- **Step 4**: Tap **"حفظ" (Save)**. Your subject card will appear with its distinct color.

### 2. Setting Up a Lecture
- **Step 1**: Tap on your new Subject card. You are now inside the **Lectures Screen**.
- **Step 2**: Tap the **+** button at the bottom.
- **Step 3**: The app automatically suggests the next lecture number. You can change this, add a lecture name, or adjust the date and time.
- **Step 4**: Tap **"حفظ" (Save)**. The app will immediately take you into that lecture's photo grid.

### 3. Capturing and Managing Photos
- **Step 1**: Inside the lecture, tap the **+** button. Two options will slide up:
    - **Camera (Camera Icon)**: Opens the high-speed built-in camera.
    - **Import (Library Icon)**: Opens your phone's gallery to select existing photos.
- **Step 2 (Camera)**: Point your phone at the board and tap the large white shutter button. You'll see a thumbnail of your photo appear in the strip at the bottom.
- **Step 3 (Camera)**: When finished, tap the **Check (Done)** icon to return to the grid.

### 4. Multi-Select & Sharing
- **Step 1 (Multi-Select)**: In the photo grid, **Long-Press** any photo. You are now in Selection Mode. Tap other photos to add them to your selection.
- **Step 2 (Sharing)**: Tap the **Share** icon in the top bar to send the selected photos to your classmates.
- **Step 3 (Bulk Delete)**: Tap the **Trash** icon to delete all selected photos at once.
- **Step 4 (Cancel)**: Tap the **Back Arrow** to exit selection mode.

### 5. Manual Reordering
- **Step 1**: In any list (Subjects, Lectures, or Photos), tap the **Reorder (Bars)** icon in the top bar.
- **Step 2**: Use the **Up/Down Arrows** on each item to move them to your desired position.
- **Step 3**: Tap the **Check (Done)** icon in the top bar to save your new order permanently.

### 6. Studying, Saving & Inspecting
- **Step 1**: Tap any photo in the grid to open the **Full-Screen Viewer**. Note that your status bar disappears for focus.
- **Step 2 (Zooming)**: Tap the **Magnifying Glass** icon to enter **Zoom Mode**. Pinch to zoom and pan. Toggle it off to resume swiping between photos.
- **Step 3 (Rotating)**: Tap the **Rotate** icon. This physically rotates the photo file on your device.
- **Step 4 (Saving to Phone)**: Tap the **Download (Arrow Down)** icon. The photo is now saved in your phone's "Pictures/LecSnap" folder for use in other apps.
- **Step 5 (Notes)**: Tap the **Note** area at the bottom. Use the check icon next to the text box to save your notes.

### 7. Settings & Data Safety
- **Step 1**: From the home screen, tap the **Settings (Gear)** icon.
- **Step 2**: Tap **"تصدير البيانات" (Export)** to create a `.zip` backup of your entire app.
- **Step 3**: Use **"استيراد" (Import)** on a new phone to restore all your subjects, lectures, and photos instantly.

---
*Created with passion for better education.*
