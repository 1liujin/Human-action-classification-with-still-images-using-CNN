# Human-action-classification-with-still-images-using-CNN
In recent years, one of the most difficult problems in computer vision has been automatic human action and activity recognition. It is critical in a variety of artificial intelligence applications, including video surveillance, computer games, robotics, and human-computer interactions. Research into intelligent surveillance has resulted from the growing demand for safety and protection. Feature extraction, action representation, and classification are the three major steps of an action recognition system. As a result, each step is critical to achieving a high recognition rate. Raw data is fed into a feature vector by the feature extraction and action representation models. The classification result would be greatly influenced by the proper extraction and selection of features. In this research seven human activities are chosen from a custom dataset made by the author in order to create an optimal human action detection model. The activities are yawning, phoning, sitting, standing, walking, running and hand waving. In order to get a benchmark result for our model conventional methods such as Naive Bayes, Support Vector Machine (SVM), K-nearest Neighbor (KNN), Random Forest, Gradient Boosting and Decision Tree were used. After that deep learning models such as ResNet, AlexNet, VGG16 and DenseNet were used. Next I used ResNet50 for feature extraction and then classified the dataset using SVM. Finally, in order to outperform the other methods, a custom CNN model was introduced. The best result came from the custom CNN model. The custom Convolutional Neural Network (CNN) model gave 80\% accuracy.

Output of Ecah Layer of the CNN Model
![1](https://user-images.githubusercontent.com/26010539/114314953-aa18ac80-9b1e-11eb-9016-946803cbdd15.png)
![2](https://user-images.githubusercontent.com/26010539/114314964-bc92e600-9b1e-11eb-985a-a1368bbe6555.png)
![3](https://user-images.githubusercontent.com/26010539/114314965-be5ca980-9b1e-11eb-99d7-b1e4316bc020.png)
![4](https://user-images.githubusercontent.com/26010539/114314967-bf8dd680-9b1e-11eb-9468-f13379dc6672.png)
![5](https://user-images.githubusercontent.com/26010539/114314968-c0266d00-9b1e-11eb-9df5-b0f35f940061.png)
![6](https://user-images.githubusercontent.com/26010539/114314969-c0bf0380-9b1e-11eb-9238-203a40ef50c6.png)
![7](https://user-images.githubusercontent.com/26010539/114314971-c1579a00-9b1e-11eb-82e4-5117495356da.png)
![8](https://user-images.githubusercontent.com/26010539/114314973-c288c700-9b1e-11eb-8bcc-f76c53f39c59.png)
![9](https://user-images.githubusercontent.com/26010539/114314975-c288c700-9b1e-11eb-9947-a8fb8090098b.png)
![10](https://user-images.githubusercontent.com/26010539/114314977-c3215d80-9b1e-11eb-8314-e770289b7f88.png)
![11](https://user-images.githubusercontent.com/26010539/114314978-c3b9f400-9b1e-11eb-9041-16b6367436b0.png)
![12](https://user-images.githubusercontent.com/26010539/114314979-c4528a80-9b1e-11eb-9542-2195683dfc22.png)

Dataset Ratio
![dataset](https://user-images.githubusercontent.com/26010539/114316265-9ec87f80-9b24-11eb-84b7-a90d1dcc0fe9.JPG)

CNN Model Archticture
![model](https://user-images.githubusercontent.com/26010539/114316266-9ff9ac80-9b24-11eb-929d-c4a54ae962ff.png)

CNN Confusion Matrix
![CNN con_mat](https://user-images.githubusercontent.com/26010539/114316268-a0924300-9b24-11eb-8ba9-9e12e69ed13c.png)
