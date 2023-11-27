# Face Sawp with AI by [@Hillobar](https://github.com/Hillobar)
The ultimate guide to getting started with AI face swapping technology in the comfort of your own PC or Laptop (Nvidia GPU Cards Only!)

> [!IMPORTANT]
> Code is owned by [@Hillobar](https://github.com/Hillobar/Rope) and I've personally tested it myself, and it's completely safe to use. Please make sure you have an above 20 series graphics card to function with this software. Recommend **RTX 3050 Ti** or above.

# Get Started
Here is the full starting guide to get started. Follow along with the process.

# Installation - Windows 10/11

## Step 1 - Essentials
> [!NOTE]
> Please ignore this part if you have already installed all the required libraries

- Install [FFMPEG](https://www.gyan.dev/ffmpeg/builds)
- Install [CUDA Toolkit 11.8](https://developer.nvidia.com/cuda-11-8-0-download-archive)
- Install [cuDNN v8.5 for CUDA 11.x](https://developer.nvidia.com/rdp/cudnn-archive)

## Step 2
Clone the repository to your PC/Laptop
```sh
git clone https://github.com/Hillobar/Rope.git
```
## Step 3
Navigate to the file location
```sh
cd yourfilename
```
## Step 4
Set up a local venv
```sh
python.exe -m venv venv
```
## Step 5
Activate your new venv
```sh
.\venv\Scripts\activate
```
## Step 6
Install all dependencies 
```sh
.\venv\Scripts\pip.exe install -r .\requirements.txt
```
## Step 7
- Download the AI models from [**Here**](https://github.com/Hillobar/Rope/releases/download/Sapphire/models.zip)
- Then extract the files and place all model files inside your model folder on the project
## Step 8
- You're at the end of the line. Just doubble click on the `Rope.bat` and let it run!
- Wait till the UI pops up and you're ready to use the software
