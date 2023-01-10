# Super-resolution image reconstruction for Earth observation
## Final project for CS-GY 6433 - Computer Vision (Spring 2022)

This project implements a deep residual network (WDSR-3D) for performing 3x super-resolution of red and near-infrared spectrum satellite imagery. The submitted model (found under `/models`) achieves cPSNR score of 50.44.

All code for the project can be found in the Jupyter notebook found in the project root. The notebook was run on Google Colab GPU instance. Note: A high-memory instance is required to handle the size of the dataset. For full report, see `/publish/final_report.pdf`. 

### TODOs

- [ ] Experiment with different data augmentation (e.g., no shuffle of image inputs in order to maintain temporal coherence)
- [ ] Incorporate GAN for fine-tuning
