# knowledge-distillation-DenseNet

# Dependencies Installation Guide

This project requires several Python packages to run. All dependencies are listed in the `requirements.txt` file.

## Prerequisites

- Python 3.10.14
- pip (Python package installer)

## Installation

To install all required dependencies, run the following command in your terminal:

## Key Dependencies

The project uses several important libraries including:

- **TensorFlow** (tensorflow-macos==2.15.0, tensorflow-metal==1.1.0)
  - Deep learning framework optimized for macOS
  
- **Data Processing & Analysis**
  - numpy==1.26.4
  - pandas==2.2.3
  - scikit-learn==1.5.2
  - scipy==1.13.1
  
- **Visualization**
  - matplotlib==3.8.4
  - seaborn==0.13.2
  
- **Image Processing**
  - pillow==10.3.0

## Note

- The requirements include specific versions that have been tested and verified to work together
- Some packages may have their own dependencies which will be automatically installed
- The `tensorflow-macos` and `tensorflow-metal` packages are specifically for macOS systems. For other operating systems, you may need to install the standard `tensorflow` package instead.


## Installation Steps

1. Clone or download the repository to your local machine
```bash
   git clone <repository-url>
```
2. Navigate to the project directory in your terminal:
```bash
   cd <project-folder>
```
3. Install dependencies

```bash
   pip install -r requirements.txt --user
```

## Troubleshooting

If you encounter any installation issues:

1. Make sure your pip is up to date:
```bash
python -m pip install --upgrade pip
```
