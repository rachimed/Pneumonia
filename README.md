# Diagnosing Pneumonia Using X-Ray Images

X-ray images allow for the visualization of pneumonia signs, thus confirming the diagnosis and identifying the type and stage of the disease. 
Unlike other proven effective diagnostic methods, X-ray images are more accessible. However, since the signs of pneumonia and other lung diseases on X-ray images
are similar, this type of study only constitutes part of a complete diagnosis.

To diagnose, a specialist needs:

- Shape and size of lung fields (within normal limits or note deviations from the norm)
- Lung fields are transparent or deviations from the norm are detected in the form of: shadows, clearances, symptoms of mixed shadows.
- Study of lung profile (improved, impoverished, or normal)

The neural model does not need this data. It does not require an in-depth examination of the image; the diagnosis will be announced instantly. Once built and trained,
it predicts the outcome with reasonable accuracy.

## Project Content:

- Pneumonia detection model: pneumonia_detection_model and pneumonia_model2.h5
- Pneumonia classification model: pneumonia_classification_model (viral or bacterial)

The models are trained on 5000 pneumonia images and 1600 non-pneumonia images. The dataset is enriched with viral pneumonia images. The test folder contains external 
X-ray images (freely accessible images on the Internet).
The base models chosen for the classification model in this project are ResNet50 and VGG16, capable of handling problems of an order of magnitude more complex.

The models were trained using Google Colab.
Colab provides access to powerful GPU resources, making it suitable for training deep learning models efficiently.
