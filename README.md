# Real-World Object Tagging with CCL

A computer vision project that performs **real-world object detection and tagging** using **Connected Component Labeling (CCL)** — applied to various real-world images including cars, coins, binary images, and more.

---

## Overview

Connected Component Labeling (CCL) is an image processing technique used to detect and label distinct objects in binary images. This project applies CCL to real-world scenarios to identify, tag, and annotate objects across different image types.

---

## Project Structure

```
├── 22i-2034.ipynb                    # Main Jupyter notebook
├── 22i2034_SOHAIB_report_Assignment1.pdf  # Project report
├── original_image.jpg                # Input image
├── binary_image.jpg                  # Binarized version
├── bounding_boxes.jpg                # Objects with bounding boxes
├── colored_components.jpg            # Labeled components (colored)
├── final_annotated.jpg               # Final annotated output
├── car.jpg / cars.jpg                # Car detection samples
├── coins.jpg                         # Coin detection sample
├── selfie.jpg                        # Selfie detection sample
├── plate.webp / ai.webp              # Additional test images
└── README.md
```

---

## Pipeline

```
Input Image → Grayscale → Binarization → CCL → Bounding Boxes → Annotated Output
```

---

## Features

- Binary image generation from real-world images
- Connected Component Labeling to detect distinct objects
- Colored component visualization
- Bounding box drawing around detected objects
- Tested on multiple real-world image types (cars, coins, plates, faces)

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sohaib0075/Real-World-Object-Tagging-with-CCL.git
   ```

2. Install dependencies:
   ```bash
   pip install numpy opencv-python matplotlib jupyter
   ```

3. Open the notebook:
   ```bash
   jupyter notebook 22i-2034.ipynb
   ```

---

## Results

> See `22i2034_SOHAIB_report_Assignment1.pdf` for full results and analysis.

Sample outputs include:
- `colored_components.jpg` — each detected object labeled with a unique color
- `bounding_boxes.jpg` — bounding boxes drawn around all detected objects
- `final_annotated.jpg` — final tagged output image

---

## Tech Stack

- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Author

**Sohaib Shahzad** — [@sohaib0075](https://github.com/sohaib0075)

---

## License

This project is open source and available under the [MIT License](LICENSE).
