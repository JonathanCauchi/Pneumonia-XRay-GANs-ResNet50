# Pneuomia-XRay-GANs-ResNet50
Using Conditional GAN to generate synthetic data from provided penumonia/normal chest x-rays (Kaggle). Utilized pre-trained ResNet50 (ImageNet) to classify pneumonia from actual and generated images. Obtained 98% accuracy on train and validation sets for real and fake datasets

Correction: ResNet Model should have 1 unit (not 2) for the sigmoid layer, and the added dense layer should have less than 2048 nodes (maybe 1024). Also try out adding more layers or chaning the pre-trained model structure.
