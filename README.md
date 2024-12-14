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

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/31789019/6d3787ed-8960-4d29-93b0-d82f993f3fa4/project-report-cs512-f24.pdf
[2] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/31789019/393caaa0-51a4-41c7-9ae3-600dae8ad18d/Resume.pdf
