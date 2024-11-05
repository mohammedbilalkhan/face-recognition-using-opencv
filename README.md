# Face Recognition System Using OpenCV

## Project Overview
This project explores face recognition using OpenCV, an open-source computer vision library. With the rising demand for robust security systems and seamless user authentication, face recognition technology has become increasingly relevant. This project leverages the capabilities of OpenCV to build an efficient and accurate face recognition system that could be applied in areas such as biometric authentication, surveillance, and personalized user experiences.

## Dataset
The dataset for this project consists of face images of multiple celebrities, scraped from Pinterest. It includes:
- **Total Images**: 17,534 face images
- **Total Classes**: 105 unique celebrities

This dataset provides a diverse set of facial features and variations, making it ideal for training and evaluating the face recognition system.

## Methodology
1. **Data Preprocessing**: The face images were resized, normalized, and labeled to maintain consistency. Data augmentation techniques were applied to improve model generalization.
2. **Face Detection**: Used OpenCV’s Haar Cascade Classifier to detect faces in each image, ensuring that only relevant face regions were processed.
3. **Face Recognition**: Trained an **LBPHFaceRecognizer** (Local Binary Pattern Histogram), which is effective in capturing texture patterns essential for identifying distinct facial features.
4. **Evaluation**: Evaluated model performance using accuracy and precision metrics to gauge its effectiveness in recognizing faces from the dataset.

## Results and Achievements
The face recognition system built with OpenCV demonstrated reliable performance, achieving high accuracy in identifying faces across the celebrity dataset. The LBPHFaceRecognizer’s adaptability to different facial features and variations in lighting conditions makes it a strong choice for applications requiring consistent recognition accuracy.

## Conclusion
This project showcases the potential of OpenCV in building a secure and efficient face recognition system. By integrating the Haar Cascade classifier for face detection with LBPHFaceRecognizer for identification, we achieved a robust solution suitable for practical biometric authentication. The project's success in adapting to diverse facial features and lighting conditions sets a solid foundation for further advancements in face recognition technology.

---

## Future Work
Future directions for enhancing this project could include:
- Experimenting with more complex architectures like CNN-based models for improved accuracy.
- Expanding the dataset to include more varied facial expressions and angles.
- Exploring real-time face recognition implementations for live video feeds.

---

## Acknowledgments
If you have any questions or suggestions, please feel free to open an issue or contact mohammedbilalkhan10@gmail.com.

Happy analyzing and predicting!
