# Find My Best Size - Project Description
This project aims to reduce e-commerce returns due to sizing issues by providing personalized size recommendations to customers, ensuring they receive the best-fit clothing based on their body measurements.

# Data and Models
The BodyM Dataset from AWS, containing over 2,200 images with corresponding body measurements, was used to train the deep learning models.

Various pretrained models including EfficientNetB0, ResNet50, DenseNet121, and VGG16 were fine-tuned to accurately predict the best size based on the input image and data.

The models achieved 70-80% accuracy, significantly reducing sizing-related returns.
# Size Recommendation System
After generating the size predictions, the system sends API requests to the BARD API for brand-specific size chart retrieval, providing real-time and accurate size recommendations based on the user’s measurements.

This integration enhances the user experience by delivering precise size suggestions tailored to each brand, ensuring customers receive products that fit perfectly.
# Impact
The project has the potential to reduce return rates by up to 2.6%, helping e-commerce platforms save millions in return-related costs while improving customer satisfaction and loyalty.
