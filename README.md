# DR_multiclass_classification
Multiclass classification of Diabetic Retinopathy Disease under single GPU constraints. 
Trained a Multiclass classification ensemble model using 4 models (InceptionV3, ResNet152, EfficientNet-B7 and DenseNet169) and achieved 65% accuracy. 
With ViT got an accuracy of 70%.
Implemented advanced pre-processing techniques such as CLAHE and Ben-Graham’s method.
Developed a custom approach that improved validation accuracy over these existing techniques.
Performed data augmentation (on Eyepac dataset) using cut-mix; improved class-balanced dataset size
by 5X.

For final result check ensemble_cut.ipynb and ensemble.ipynb and vit.ipynb

