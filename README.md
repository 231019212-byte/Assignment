---

## Method
1. Load images using Keras ImageDataGenerator  
2. Rescale pixels (0–1) and resize images (150x150)  
3. Apply data augmentation (rotation, zoom, flips)  
4. Build CNN: Conv2D + MaxPooling + Flatten + Dense layers + Sigmoid output  
5. Compile model (optimizer: Adam, loss: binary_crossentropy, metric: accuracy)  
6. Train on train/ set, validate on val/ set  
7. Evaluate on test/ set using Accuracy, Confusion Matrix, and Classification Report
