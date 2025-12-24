# Lesion Master

**Lesion Master** is a professional-grade desktop application designed for medical image analysis and annotation. Developed for researchers, clinicians, and imaging professionals, it combines intelligent superpixel segmentation with an intuitive interface to accelerate Region of Interest (ROI) marking workflows.

The tool supports standard images, **DICOM** series, and **NIfTI** volumes, making it a versatile solution for medical image segmentation tasks.

---

## Key Features

  - **Intelligent Segmentation**: Utilizes **SLIC Superpixel** technology to automatically snap annotations to tissue boundaries, reducing manual effort.
  - **Comprehensive Format Support**: Seamlessly handles **DICOM** folder series, **NIfTI** 3D volumes (.nii.gz), and standard image formats (PNG, JPEG, BMP).
  - **Advanced Annotation Tools**: Includes **Lasso**, **Rectangle**, and **Ellipse** tools for region selection, plus **Pixel-level Brush** and **Eraser** tools for fine-tuning.
  - **Smart Export**: Automatically detects export needs—saving as binary masks, distinct-color RGB masks, or full DICOM series with preserved metadata.
  - **Volume Navigation**: Built-in multi-slice navigation for 3D medical volumes with smooth zoom and pan controls.

---

## Installation

### Windows Installation

1.  **Download the Software**:
    Download the latest **Lesion Master** executable (.exe) using the link below:
    **[Download Lesion Master](https://github.com/Akhil717/Lesion-Master/actions/runs/19888382984/artifacts/4748552332)** 2.  **Extract/Run**:
      * If the download is a `.zip` file, extract the contents to a folder.
      * Double-click `LesionMaster_Setup.exe` (or the application executable) to launch.

3.  **Follow Setup**:
    Follow the on-screen prompts to complete the installation.

4.  **Launch**:
    Open **Lesion Master** from your Start Menu or Desktop shortcut.

### System Requirements

  - **OS**: Windows 10 or later (64-bit).
  - **RAM**: 4 GB minimum (8 GB recommended for large 3D volumes).
  - **Disk Space**: 500 MB free space.

---

## How to Use

1.  **Load Data**: Go to `File → Load Image` (Ctrl+O) and select a file or a DICOM folder.
2.  **Annotate**: Use the **Lasso** tool (default) to draw around regions. The system automatically segments the area using superpixels.
3.  **Refine**: Use the **Brush** tool to add specific pixels or the **Eraser** tools (Superpixel/Pixel) to correct mistakes.
4.  **Export**: Go to `File → Export` (Ctrl+S) to save your masks as images, NIfTI volumes, or DICOM series.

**[Download User Manual](https://drive.google.com/file/d/1Oqi0TCoILgV-mzj19y0dEesy5G-TiLuH/view?usp=share_link)**

---

## Citation

If you use **Lesion Master** in your research, please cite it as follows:

```bibtex
@software{akhil2025lesionmaster,
  author = {Akhil},
  title = {Lesion Master: Advanced Medical Image Annotation Tool},
  year = {2025},
  version = {1.9.0},
  note = {IISc Bangalore}
}
