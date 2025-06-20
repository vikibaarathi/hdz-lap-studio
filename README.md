# HDZero Lap Studio

HDZero Lap Studio is a cross-platform mobile app (Flutter) built for FPV drone pilots using HDZero goggles. It allows users to import 90FPS DVR recordings, convert them to 30/60FPS, manually mark lap times, and export videos with lap overlays for review or sharing.

---

## ✨ Key Features

- 📥 Import DVR recordings directly from an SD card
- 🎞 Convert 90FPS video to 30FPS or 60FPS
- ⏱ Frame-accurate lap timing using a jog wheel UI
- 📝 Overlay lap data directly onto the video
- 📤 Export and share annotated videos to your gallery or social media

---

## 🚀 Tech Stack

- **Framework:** Flutter (iOS & Android)
- **Video Processing:** FFmpegKit (via flutter_ffmpeg)
- **Playback:** video_player / chewie
- **File Handling:** file_picker, path_provider

---

## 📦 Project Structure (Clean Architecture)

lib/
├── core/
├── features/
│ ├── import/
│ ├── conversion/
│ ├── timing/
│ ├── overlay/
│ └── export/
├── shared/
└── main.dart

yaml
Copy
Edit

---

## 🛠 Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/hdzero-lap-studio.git
   cd hdzero-lap-studio
Install dependencies

bash
Copy
Edit
flutter pub get
Run on device

bash
Copy
Edit
flutter run
Build APK / iOS

bash
Copy
Edit
flutter build apk   # For Android
flutter build ios   # For iOS (Mac only)
📸 Screenshots (Coming Soon)
📍 Roadmap
 Project initialization

 DVR import module

 FPS conversion logic

 Jog wheel UI

 Lap overlay + video export

 Social media sharing

👨‍💻 Author
Viki Baarathi
Product Owner & Lead Developer
Callsign: Barracuda

