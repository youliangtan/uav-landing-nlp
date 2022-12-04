# uav-landing-nlp
Guided UAV Landing with Natural Language Instructions

There are two ML components here
 - CLIP (`cd clip` and check out docs there)
 - DeepLabv3 Semantic seg (checkout the jupyter notebook)

Dataset:
 - `aerial-sematic-segmentation-dataset`
   - Use for  `segmentic Segmentation`
   - https://www.kaggle.com/datasets/bulentsiyah/semantic-drone-dataset
 - `semantic_drone_dataset_processed`:
   - Use for `CLIP`
   - [link](https://drive.google.com/drive/folders/1CwQwrTuoVC0FptFpd1qd0Mx1VR9EuHyv)
   - Consist of redcross on aerial image to describe spatial info
