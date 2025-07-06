# OpenCV Color Detection Utility

This project provides a simple utility function `get_limits()` to make color-based object detection in OpenCV super easy.  
Just pass the RGB value of the color you want to detect (e.g., green, yellow, white), and get the correct HSV lower and upper limits for masking!

---

## Features

- 📷 **Real-time color detection** with OpenCV and your webcam.
- 🎨 **Detect any color** easily: pass the RGB list (e.g., `[0,255,0]` for green).
- ⚡ **Built-in support** for tricky colors like white and black.
- 🔥 Simple to use in your OpenCV scripts!

---

## Setup

1. **Clone or download** this repo.
2. **Install dependencies** (recommended in a virtual environment):

    ```bash
    pip install opencv-python numpy pillow
    ```

3. **Project structure:**
    ```
    .
    ├── main.py
    ├── util.py
    └── README.md
    ```

---

## Usage

### 1. Import the function

```python
from util import get_limits
