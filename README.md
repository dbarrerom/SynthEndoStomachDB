# SyntheticStomachDataset
A realistic synthetic endoscopy dataset from CT-derived 3D stomach models, with GAN-based gastric textures, depth maps, and 6-DoF poses.
This repository contains the **Synthetic Stomach Endoscopy Dataset**, a realistic virtual endoscopy collection generated from 3D stomach models reconstructed from abdominal CT scans. Gastric mucosa textures were synthesized using **Infinite Texture GANs** trained with real endoscopic mucosa patches.

## Dataset Overview
- **30** virtual endoscopy videos (2–3 min each).
- RGB frames (720×720 px, 15 fps).
- Depth maps aligned with RGB frames.
- 6-DoF camera pose annotations.

## Pipeline
![Pipeline](docs/pipeline.png)

## Download
The dataset is available to create the 
