**DS 4002, Spring 2026** <br>
**Group Name**: Freenor's Fourth Years <br>
**Group Leader:** Abby Goss <br>
**Members:** Christina Barton, Abby Goss, Rohan Kohli

# Project 3: Binary Waste Classification Using CNNs and the RealWaste Dataset

The goal of this project is to explore whether a convolutional neural network can accurately determine whether a piece of waste is recyclable or non-recyclable based on images from the RealWaste dataset. We build a binary image classifier that predicts Recyclable vs. Non-Recyclable from real-world landfill images. We first build a baseline custom CNN, then compare it against transfer learning from a pretrained MobileNetV2. Although the original dataset has nine material classes, we converted it into a binary target to align with the practical goal of automated waste sorting. Model performance is evaluated using accuracy and F1 score.

## Documentation Map
Main Branch Folders
- Data
  - Link to dataset
  - Data Appendix 
- Scripts
  - eda_project_3.ipynb (exploratory data analysis)
  - Model.py (preprocessing, model training, and evaluation)
- Output
  - ClassDistributionCleaned.png
  - ClassDistributionOriginal.png
  - NonRecyclableExamples.png
  - RecyclableExamples.png
  - confusion_matrices.png
  - loss_curves.png
 
## References 
[1] “UCI Machine Learning Repository,” Uci.edu, 2023. https://archive.ics.uci.edu/dataset/908/realwaste <br>
[2] Environmental Protection Agency, “National Overview: Facts and Figures on Materials, Wastes and Recycling | US EPA,” United States Environmental Protection Agency, Nov. 08, 2024. https://www.epa.gov/facts-and-figures-about-materials-waste-and-recycling/national-overview-facts-and-figures-materials <br>
[3] Z. Keita, “An Introduction to Convolutional Neural Networks (CNNs),” Datacamp, Nov. 14, 2023. https://www.datacamp.com/tutorial/introduction-to-convolutional-neural-networks-cnns
