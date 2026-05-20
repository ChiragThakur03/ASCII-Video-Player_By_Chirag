# 🎬 ASCII Video Player

A powerful, cross-platform Python application that transforms your videos into stunning ASCII art animations. Watch videos directly in your terminal or export them as stylized MP4 files.

![ASCII Preview Placeholder](https://via.placeholder.com/800x400?text=ASCII+Video+Player+Preview)

## ✨ Features

- **Live Terminal Playback:** Experience your favorite videos as high-speed ASCII animations in your command line.
- **24-bit True Color:** Uses ANSI escape codes to render characters with the original video's colors.
- **MP4 Export:** Convert and save your ASCII animations as high-quality MP4 video files.
- **Customizable Output:** 
  - Adjust output width (Manual or Auto-fit to terminal).
  - Frame skipping for smoother performance on older hardware.
  - Custom background colors for exported videos (Black, White, Blue, or Hex).
- **Multilingual UI:** Clean, English-focused interface with a professional startup logo.

## 🚀 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/ChiragThakur03/ASCII-Video-Player_By_Chirag.git
cd ASCII-Video-Player
```

### 2. Install Dependencies
Make sure you have Python 3.7+ installed. Then, install the required libraries:
```bash
pip install -r requirements.txt
```

## 🛠️ Usage

### Quick Start
To play a video in your terminal, simply run:
```bash
python ASCII_V1.py your_video.mp4
```

## 🔄 User Flow

The application is designed to be intuitive and guided. Here is the typical flow:

1.  **Launch:** You run the script from the command line, providing your video file as an argument.
2.  **Branding:** A professional "ASCII PLAYER" logo appears for 2 seconds while the engine initializes.
3.  **Setup Phase:** The script prompts you for three configuration settings:
    *   **Output Width:** Press `Enter` to automatically scale the video to fit your terminal window, or specify a width in characters.
    *   **Frame Skipping:** Set a number (e.g., `2`) to skip frames for smoother playback on slower terminals.
    *   **Looping:** Choose if the preview should automatically restart when finished.
4.  **Live Preview:** The video plays in your terminal using colored ASCII characters.
    *   You can stop the preview at any time by pressing **Ctrl+C**.
    *   A progress bar at the bottom keeps you updated on the playback status.
5.  **Export Phase:** Once the preview ends, you are asked if you want to export the animation as an MP4 file.
    *   **Folder Selection:** Specify where to save the output.
    *   **Background Style:** Choose a background color (Black, White, Blue, or Custom Hex).
    *   **Rendering:** The script draws the ASCII art onto high-resolution images and compiles them into a video.
6.  **Finalization:** The path to your new `.mp4` file is displayed, and you can choose to process another video or exit.

## 📦 Requirements
- `opencv-python`: Video processing and I/O.
- `numpy`: High-speed color calculations.
- `Pillow`: Image rendering for export.

## ⚖️ License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

Copyright (c) 2026 **Chirag Bahadur**
