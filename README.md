# acne-detection-and-severity-grading
# Acne Detection and Severity Grading using Deep Learning

This project implements a two-stage system for acne analysis on smartphone images:

1. Faster R-CNN with ResNet50 backbone for acne lesion detection
2. LightGBM classifier for severity grading

## Features

- Detects and classifies four acne types: blackheads/whiteheads, papules/pustules, nodules/cysts, and acne scars
- Grades overall acne severity using the Investigator's Global Assessment (IGA) scale
- Utilizes the ACNE04 dataset with 1,572 images and 41,000 labeled acne lesions

## Performance

- Acne Detection: 24.81% mean Average Precision (mAP)
- Severity Grading: 91% overall accuracy


## Future Work

- Improve model performance through data augmentation and hyperparameter tuning
- Enhance dataset diversity, particularly for severe acne grades
- Optimize for mobile deployment

## Contributors

- Anayna Nidhi Singh
- Narasimha Karthik G

