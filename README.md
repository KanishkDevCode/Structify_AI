# Structify_AI
# FloorPlan-Interpreter

Automated floor plan analysis and CAD/BIM export using deep learning and vectorization.

## Features

- Image preprocessing (OpenCV, PIL)
- Deep learning segmentation (U-Net, Mask R-CNN, TensorFlow/PyTorch)
- Vectorization (OpenCV, Shapely)
- CAD/BIM export (.dwg, .ifc via FreeCAD, IfcOpenShell)

## Datasets

- [Wall Segmentation Dataset](https://app.roboflow.com/kanishk-wfmyz/wall_dataset_05-09-24-lmfa4)
- [Floor Plan Segmentation Dataset](https://app.roboflow.com/kanishk-wfmyz/floor_plan_segmentation_final-dij0o)

## Getting Started

1. Clone the repo:

2. Install requirements:

3. Download datasets (see `data/README.md`).

4. Run notebooks or scripts in `src/` for each stage.

## Directory Structure

- `data/`: Dataset info and download scripts
- `notebooks/`: Jupyter notebooks for each workflow stage
- `models/`: Pre-trained and custom-trained models
- `src/`: Python scripts for modular workflow
- `requirements.txt`: List of dependencies

## License

[MIT License](LICENSE)

