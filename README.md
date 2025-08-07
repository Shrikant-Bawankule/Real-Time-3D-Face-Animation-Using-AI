# 🎭 Real-Time 3D Face Animation Using AI

This project brings static faces to life by generating real-time 3D facial animations using a deep learning model. Built on top of the **First Order Motion Model**, it takes a source image (e.g., a portrait) and a driving video (e.g., someone nodding or talking) to animate the image with the motion in the video.

## 📌 Features

- Generates realistic facial animations from a single image
- Uses driving video to replicate facial expressions and motion
- User-friendly interface with widgets in Google Colab
- Output as downloadable `.mp4` video

## 🧠 Tech Stack

| Category       | Tools / Libraries                       |
|----------------|------------------------------------------|
| Deep Learning  | PyTorch, pretrained checkpoints (FOMM)   |
| Animation      | imageio, ffmpeg-python                   |
| Interface      | ipywidgets, IPython Display, Gradio      |
| Platform       | Google Colab                             |

## 🚀 How It Works

1. **Upload a source image** (portrait photo)
2. **Upload a driving video** (person with desired facial movements)
3. **Run the notebook cells** to:
   - Load model checkpoints
   - Generate animated frames
   - Save & display result as video
  
## 🧪 Sample Use Case
Input: Anime face image + a video of someone smiling

Output: A video of the anime character smiling

## ⚠️ Ethical Consideration
This project is for educational and creative purposes only. Be mindful of how animated faces are used — misuse for impersonation or misinformation is strictly unethical.

## 👨‍💻 Author - Shrikant Bawankule




