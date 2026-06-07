# Volume

A command-line utility written in C designed to modify the volume of `.wav` audio files by scaling 16-bit PCM samples. Developed as part of the Harvard CS50 curriculum.

## Technical Specifications
* **Language:** C (Standard C99)
* **File Format:** RIFF (WAV)
* **Data Processing:** * **Header:** 44-byte fixed-size processing.
    * **Samples:** `int16_t` (signed 16-bit integers).
    * **Time Complexity:** $O(n)$, where $n$ is the number of audio samples.
    * **Space Complexity:** $O(1)$ (streaming processing).

## Getting Started

### 1. Clone the repository
```bash
git clone [https://github.com/YOUR_GITHUB_USERNAME/volume.git](https://github.com/YOUR_GITHUB_USERNAME/volume.git)
```
### 2. Change directery
```bash
cd volume
```
### 3. Compile the code
```bash
clang volume.c -o volume
```

### 4. Usage 
```bash
./volume input.wav output.wav 2
```
