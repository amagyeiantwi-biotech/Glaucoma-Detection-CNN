Glaucoma Detection Using Deep Learning

A CNN-based model for detecting glaucoma from retinal fundus images, built as part of my independent research at Northeastern University.

About

During my clinical practice as an optometrist, I examined thousands of patients with glaucoma and other retinal diseases. This project explores how AI can assist in early detection by flagging high-risk cases for follow-up.

Model & Data

Architecture: EfficientNetB0 with transfer learning

Data: 2,070 fundus images from REFUGE, ORIGA, G1020 (24% glaucoma)

Techniques: Two-phase training, data augmentation, class-weighted loss

Results

AUC: 63.9% | Sensitivity: 76.2% | Specificity: 44.4% | Accuracy: 52.2%

Correctly identified 77 of 101 glaucoma cases; false positives flagged for follow-up

Next Steps

Visualize model focus with Grad-CAM

Test on independent datasets

Extend to multi-class glaucoma severity classification

Integrate OCT data and ensemble models

Run the Notebook

Open in Colab

Requirements: TensorFlow, Keras, NumPy, Pandas, scikit-learn, Matplotlib, Seaborn

Contact

David Amagyei-Antwi – LinkedIn
 | amagyeiantwi.d@northeastern.edu
