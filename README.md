# AIMECORAL Dataset

This repository contains two datasets (AIMECORAL1 and AIMECORAL2) used for coral reef monitoring and analysis. The datasets were collected as part of the Artificial Intelligence for Marine Ecosystems (AIME) project and Track Changes initiative.

## Dataset Overview

### AIMECORAL1
- **Size**: 580 images
- **Source**: 
  - 400 original images from research expeditions
  - 180 augmented images
- **Location**: La Reunion and scattered islands in the Indian Ocean
- **Content**: 
  - Underwater images of coral reefs
  - Various coral reef conditions
  - Different coral health states
  - Multiple reef habitats
  - Various depths and lighting conditions
- **Augmentation**: 
  - Resizing
  - Rotation
  - Blurring
- **Diversity**: 
  - Multiple coral species
  - Various colony sizes
  - Different orientations

### AIMECORAL2
- **Size**: 282 images
- **Source**:
  - 200 newly captured images
  - 82 augmented images
- **Location**: New Caledonia, Pacific Ocean
- **Content**:
  - Video transect frames
  - Both soft and hard corals
  - Recent observations
- **Annotation**: Label Studio framework
- **Augmentation**:
  - Resizing
  - Rotation
  - Blurring

## Dataset Structure
```
AIMECORAL/
├── AIMECORAL1/
│   ├── original_images/     # 400 original images
│   └── augmented_images/    # 180 augmented images
└── AIMECORAL2/
    ├── original_images/     # 222 original images
    └── augmented_images/    # 60 augmented images
```

## Data Collection
- AIMECORAL1: Derived from previous research on coral detection using YOLOv5 (Younes et al., 2024)
- AIMECORAL2: Newly captured images from video transects (Kayal et al., 2023)

## Usage
These datasets are designed for:
- Coral reef monitoring
- Coral detection and classification
- Underwater image analysis
- Training and evaluating tracking systems

## References
1. Younes et al., 2024 (AIMECORAL1 dataset)
2. Kayal et al., 2023 (AIMECORAL2 dataset)

## License
[Specify your license here]

## Contact
[Add contact information for dataset inquiries]