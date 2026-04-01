# Defect Identifier

Python utilities and notebooks for **detecting defects or differences** in images using classical computer vision and **YOLOv3** (OpenCV DNN). The workflow includes preprocessing, optional comparison logic, and a Jupyter notebook for interactive exploration (`spot_the_difference/spot_the_difference.ipynb`).

## Components

| File | Description |
|------|-------------|
| `extract_defect.py` | YOLOv3-based detection pipeline (requires `yolov3.weights`, `yolov3.cfg`, `coco.names`) |
| `preprocessing.py` | Image preprocessing helpers |
| `comparation.py` | Comparison utilities between image pairs or regions |

## Requirements

- Python 3.x  
- OpenCV (`cv2`), NumPy, Matplotlib  
- YOLOv3 weight and config files compatible with OpenCV’s `dnn` module

Download official or compatible YOLOv3 assets and place them in the working directory or update paths in `extract_defect.py`.

## Usage (outline)

1. Install dependencies: `pip install opencv-python numpy matplotlib`  
2. Ensure YOLO files are on disk and paths match `load_yolo_model()` in `extract_defect.py`  
3. Run scripts from the repository root or follow the notebook in `spot_the_difference/`

## License

See the repository license file if present.
