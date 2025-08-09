FCN_EQLocation highlights a superior approach for earthquake location compared to traditional methods like Hypo71 and NonLinLoc. By processing raw waveform data directly, FCN_EQLocation eliminates phase-picking and velocity model dependencies. Results show FCN_EQLocation achieves higher accuracy, particularly in depth determination and variable-quality data handling. Key limitations include: reliance on training data quality, reduced performance for linear seismicity trends, and slightly higher horizontal errors. Nevertheless, FCN_EQLocation represents a major advancement in automated, high-precision earthquake localization. Future work should address training biases and improve tectonic pattern interpretation.


All codes, including the data loader, model configurations, training loops, and evaluation scripts, are consolidated in the FCN_EQLocation.ipynb Jupyter Notebook for reproducibility and ease of use. This notebook integrates:

Data Preprocessing – Raw waveform loading, normalization, and segmentation.

Model Architecture – FCN layers, hyperparameters (e.g., kernel size, dropout), and PyTorch implementation.

Training Pipeline – Loss functions (e.g., MSE), optimizers (e.g., Adam), and GPU acceleration.

Evaluation Metrics – Comparison against ground truth locations (latitude, longitude, depth) and error analysis (e.g., RMSE).
