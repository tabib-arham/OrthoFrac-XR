# 🦴 OrthoFrac-XR
### A Clinically Validated Multimodal High-Resolution X-ray Dataset for Bone Fracture Detection and Localization

<p align="center">

![Dataset](https://img.shields.io/badge/Dataset-OrthoFrac--XR-blue)
![Modality](https://img.shields.io/badge/Modality-X--ray-green)
![Classes](https://img.shields.io/badge/Classes-4-orange)
![Metadata](https://img.shields.io/badge/Metadata-Available-success)
![Validation](https://img.shields.io/badge/Doctor-Validated-red)

</p>

---

## 📖 Overview

OrthoFrac-XR is a clinically validated multimodal bone fracture dataset developed to support research in computer vision, medical image analysis, and multimodal deep learning.

The dataset contains high-resolution X-ray images together with structured clinical metadata, enabling both image-only and multimodal learning approaches.

Each sample has been reviewed and validated by orthopedic specialists to ensure clinical reliability.

---

# 📂 Dataset Summary

| Property | Value |
|----------|-------|
| Dataset Name | OrthoFrac-XR |
| Imaging Modality | X-ray |
| Total Images | **1493** |
| Metadata | CSV |
| Clinical Classes | 4 |
| Validation | Orthopedic Doctor |
| Image Format | JPG |
| Original Format | DICOM |
| Annotation Type | Image-level Classification |
| Multimodal | Yes |

---

# 📊 Dataset Distribution

| Class | Samples |
|--------|---------:|
| Distal Fracture | **314** |
| Proximal Fracture | **254** |
| Post Fracture | **349** |
| Non Fracture | **576** |
| **Total** | **1493** |

---

# 📁 Repository Structure

```
OrthoFrac-XR/
│
├── distal_fracture/
│     ├── distal_1.jpg
│     ├── ...
│
├── proximal_fracture/
│     ├── proximal_1.jpg
│     ├── ...
│
├── post_fracture/
│     ├── post_fracture_1.jpg
│     ├── ...
│
├── non_fracture/
│     ├── non_fracture_1.jpg
│     ├── ...
│
└── Bone_metadata.csv
```

---

# 📝 Metadata

Each X-ray image is linked to a corresponding metadata record.

| Feature | Description |
|----------|-------------|
| ID | Image filename |
| Age | Patient age |
| Gender | Male / Female |
| Bone Type | Anatomical bone |
| Left/Right | Body side |
| Fracture Type | Clinical category |
| Visibility | Fracture visibility |
| Bone Width (mm) | Bone width measurement |
| Fracture Gap (mm) | Gap measurement |
| Primary Observation | Clinical observation |

---

# 📦 Dataset Characteristics

- High-resolution radiographs
- Clinically validated annotations
- Four fracture categories
- Multimodal dataset (images + metadata)
- Suitable for binary and multiclass classification
- Supports multimodal deep learning research
- Includes quantitative anatomical measurements

---

# 📈 Dataset Status

| Item | Status |
|------|--------|
| Image Collection | ✅ Completed |
| Data Cleaning | ✅ Completed |
| Metadata Generation | ✅ Completed |
| Doctor Validation | ✅ Completed |
| Dataset Construction | ✅ Completed |
| Public Release | ✅ Available |

---

# 🤖 Technical Validation

The technical validation was performed using a multimodal CNN architecture that combines image features with structured metadata.

### Data Split

- Training: **80%**
- Validation: **10%**
- Test: **10%**

### Training Configuration

- Multimodal CNN
- Image branch
- Metadata branch
- Feature fusion
- Oversampling
- Stratified split
- 30 training epochs

---

# 📊 Model Performance

### Overall Accuracy

**96%**

---

### Class-wise Performance

| Class | Precision | Recall | F1 Score |
|--------|----------:|--------:|---------:|
| Distal Fracture | 0.93 | 0.89 | 0.91 |
| Proximal Fracture | 0.95 | 1.00 | 0.97 |
| Post Fracture | 1.00 | 0.94 | 0.97 |
| Non Fracture | 1.00 | 1.00 | 1.00 |

---

# 🔬 Applications

The dataset can be used for:

- Bone fracture classification
- Binary fracture detection
- Multi-class fracture classification
- Medical image analysis
- Multimodal deep learning
- Computer-aided orthopedic diagnosis
- Fracture severity analysis
- Clinical AI research

---

# 💻 Code

The implementation used for technical validation is available in this repository.

---

# 📚 Citation

If you use this dataset in your research, please cite the corresponding publication.

```bibtex
@article{OrthoFracXR,
  title={OrthoFrac-XR: A Clinically Validated Multimodal High-Resolution X-ray Imaging Dataset for Bone Fracture Detection and Localization}
}
```

---

# 📄 License

Please refer to the dataset repository for licensing and usage conditions.

---

# 👨‍⚕️ Acknowledgement

We sincerely thank the participating hospitals, orthopedic specialists, radiologists, and collaborating institutions whose contributions made the creation and validation of the OrthoFrac-XR dataset possible.

---

<p align="center">

### ⭐ If this dataset contributes to your research, please consider giving this repository a star.

</p>
