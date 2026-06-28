### Jazz vs Metal Audio Genre Classification

### Project Details

**Tools:** Python, Librosa, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
**Model:** Support Vector Machine with RBF Kernel

### Overview

This project classified Jazz and Metal audio using signal-processing features and machine learning. The analysis extracted acoustic characteristics from audio files to identify patterns that distinguish both genres.

### Solution

Audio files were processed into numerical features, including RMS energy, Zero Crossing Rate, spectral centroid, bandwidth, rolloff, amplitude envelope, spectrogram statistics, and 13 MFCC coefficients.

The data was standardized, explored through PCA visualization, then classified using an SVM model with an 80:20 train-test split.

### Key Findings

The final SVM model achieved 78% accuracy on the test set. Metal achieved stronger recall because its audio features were more consistent, with higher RMS energy, Zero Crossing Rate, and spectral centroid.

Jazz showed more varied acoustic patterns and was more frequently misclassified as Metal. PCA analysis also showed that three principal components explained approximately 80% of the total feature variation.

### Learning Outcomes

This project strengthened my understanding of audio-feature extraction, MFCC analysis, spectral analysis, PCA visualization, SVM classification, and confusion-matrix interpretation.
