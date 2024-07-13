## Transfer Learning (TL)

Transfer Learning is a machine learning technique where a pre-trained model, which has been previously trained on a large dataset, is used to improve generalization in another setting. This method is particularly useful when the target dataset is smaller or when computational resources are limited.

In Transfer Learning, we start with a pre-trained model, retaining all its learned weights and parameters. Typically, we only modify the last few layers to adapt the model to the new task. The common approach is to freeze all layers except for the last layer(s), which are then retrained on the new dataset.

### Pros of Transfer Learning:

1. **Computational Efficiency:** By using a pre-trained model, we save significant computational power and time as we don't need to train the entire model from scratch.
2. **Improved Performance:** Transfer Learning leverages the knowledge gained from a large dataset, which often leads to better performance on the target task.
3. **Reduced Data Requirement:** It works well even with smaller datasets, making it ideal for scenarios where collecting large amounts of data is challenging.

### Cons of Transfer Learning:

1. **Domain Mismatch:** If the pre-trained model is from a significantly different domain, it might not transfer well to the new task, leading to suboptimal performance.
2. **Overfitting:** Fine-tuning a pre-trained model on a small dataset can sometimes lead to overfitting, especially if the model is very complex.
3. **Limited Customization:** The architecture of the pre-trained model may not be fully suitable for the new task, limiting the ability to customize or modify it extensively.
4. **Resource Intensity:** Some pre-trained models can be very large and require significant memory and storage resources, which might be a limitation for some applications.

### Example:

A model trained to recognize cars can be useful to train a model for recognizing trucks, as both have similar features such as transmission, steering wheels, and wheels.

### Source of Pre-trained Models:

You can find a variety of pre-trained models on platforms like [TensorFlow Hub](https://tfhub.dev/).

![Transfer Learning](https://github.com/user-attachments/assets/2959e55f-5180-4f00-bf54-113cae3c10e5)


*Image source: [link to the image source](https://skyengine.ai/se/skyengine-blog/128-what-is-transfer-learning)*
