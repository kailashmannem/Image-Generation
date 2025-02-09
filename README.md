# Image-Generation-Using-Stable-Diffusion-and-Comfy-UI
<br>
<h2>📌 Overview </h2>
<p>This project demonstrates image generation using Stable Diffusion within ComfyUI. ComfyUI provides a node-based interface to experiment with different prompts, models, and settings for AI-generated images. The repository contains generated images and their corresponding prompts, along with instructions on how to use ComfyUI for generating new images.</p>
<br>
<h2>🎯 Project Objectives</h2>
• Utilize Stable Diffusion via ComfyUI for generating high-quality images.<br>
• Store generated images alongside their input prompts for reference.<br>
• Provide a structured workflow to use ComfyUI efficiently.<br>
• Ensure a fully GUI-based, node-controlled workflow without additional coding.<br>
<br>
<h2>⚙️ Tools & Technologies</h2>
• Stable Diffusion (Pre-trained text-to-image model) <br>
• ComfyUI (Node-based GUI for AI image generation) <br>
<br>
<h2>📦 Requirements </h2>
Before running ComfyUI for Stable Diffusion, ensure that your system meets the following requirements. <br>
<h3>🔧 Hardware Requirements</h3>
• Processor: A multi-core CPU (Intel i3/i5 or AMD Ryzen 5/7) or higher. <br>
• GPU: NVIDIA GPU with at least 4GB VRAM (RTX 3060 or higher recommended) for faster model inference. Works without GPU but slow processing time will be faced. <br>
• RAM: Minimum 8GB RAM (32GB recommended for handling large models) <br>
• Storage: At least 40GB of free SSD space to store models and generated images. <br>
<h3>🖥️ Software Requirements</h3>
• Operating System: Windows 10/11, Linux (Ubuntu recommended), or macOS <br>
• Programming Language: Python 3.8 or higher <br>
• AI Framework: Stable Diffusion (Hugging Face) <br>
• Interface & Workflow Engine: ComfyUI <br>
• Deep Learning Libraries: TensorFlow / PyTorch <br>
• Dependencies & Packages: NumPy, OpenCV, Matplotlib, PIL, and Hugging Face Diffusers <br>
<br>
<h2>🚀 Getting Started</h2>
<h3>1️⃣ Downloading ComfyUI</h3>
• You can download ComfyUI from their official github repository or clone it. <br>
• Unzip the package and save it in a folder. <br>
<h3>2️⃣ Downloading Stable Diffusion Model</h3>
• Head over to hugging face to find different versions of Stable diffusion. <br>
• You can download any available version of Stable diffusion. <br>
<h3>3️⃣ Linking Stable Diffusion model with ComfyUI</h3>
• Now that you have downloaded the model, head over to ComfyUI folder. <br>
• Navigate to this path: ComfyUI -> models -> checkpoints<br>
• Now move your Stable diffusion Model over the specified path. <br>
<h3>4️⃣ Loading the UI</h3>
• You can view two terminals namely "run_cpu" and "run_nvidia_gpu" at the start of the folder. <br>
• Double Click/Run "run_nvidia_gpu" if you have a Nvidia gpu in your system or else you can go with "run_cpu" to generate images using CPU. <br>
<h3>5️⃣ Generating Images</h3>
• Wait for sometime for the interface to load and show up in your browser. <br>
• It will load in your browser with a local host: 127.0.0.1:8188 <br>
• You can start giving prompts and generate images by giving suitable positive and negative prompts in the "CLIP Text Encode (Prompt)". <br>
<br>
<h2>💡 Suggestions & Queries </h2>
I highly appreciate any feedback or suggestions to improve this project! <br>
🚀 If you have:<br>
✅ Ideas for new features or improvements<br>
✅ Found bugs or issues while running the project<br>
<br>
Feel free to open an issue in this repository! <br>
I will do our best to respond as soon as possible. <br>
<hr>
Happy generating! 🎨✨
<hr>
