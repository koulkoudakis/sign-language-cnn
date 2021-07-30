# Pneumonia Classifier

**Name:** Sign Language Classifier

**Author:** Sharome Burton

**Date:** 07/30/2021

**Description:** Machine learning model used to classify hand gestures into letters from the American Sign Language database

**Kaggle:** https://www.kaggle.com/sharomeethan/sign-language-cnn

**GitHub:** https://github.com/koulkoudakis/sign-language-cnn

<img src="https://storage.googleapis.com/kagglesdsdata/datasets/3258/5337/amer_sign2.png?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=databundle-worker-v2%40kaggle-161607.iam.gserviceaccount.com%2F20210729%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20210729T192615Z&X-Goog-Expires=345599&X-Goog-SignedHeaders=host&X-Goog-Signature=4cffb7559f37946fbdadc1eda3a2870d6cab88caf9c7e4fc8609676d6e69ca5577e123342cea54e7dbbad662bf0b0a1240c8d45795b6cb7130f4dc04708c669e4c1affface3e936a2ce48ea24cab1122ac7099036b52b04a5a9b00b92aaba3a4455782c2e7a5eb8b0b11fffa115076fd563b0a3171b5a152adf3714be381c5bb9a319e2e062e5f2085e17bd3cc85994682aa5efb9a46fbddb465400e8a5f0c2722cff97d42afe40398ef43d415edbccefa4c21d403921a3e7ac9e4b9a0c5d2f1ed5bb2e9ff12319d7486521acdf1c080dc2af0779b5025627ac3f085cfcf933d58c0dbed47ccf1bd15d7d6f3887d906eada97418fd41b22c995db052b50b0e7a"
     alt="letter-examples"
     style="left; margin-right: 10px;" />

## 1. Problem definition
> How accurately can we classify hand gestures into sign language letters?

## 2. Data
The original MNIST image dataset of handwritten digits is a popular benchmark for image-based machine learning methods but researchers have renewed efforts to update it and develop drop-in replacements that are more challenging for computer vision and original for real-world applications. As noted in one recent replacement called the Fashion-MNIST dataset, the Zalando researchers quoted the startling claim that "Most pairs of MNIST digits (784 total pixels per sample) can be distinguished pretty well by just one pixel". To stimulate the community to develop more drop-in replacements, the Sign Language MNIST is presented here and follows the same CSV format with labels and pixel values in single rows. The American Sign Language letter database of hand gestures represent a multi-class problem with 24 classes of letters (excluding J and Z which require motion).

The dataset format is patterned to match closely with the classic MNIST. Each training and test case represents a label (0-25) as a one-to-one map for each alphabetic letter A-Z (and no cases for 9=J or 25=Z because of gesture motions). The training data (27,455 cases) and test data (7172 cases) are approximately half the size of the standard MNIST but otherwise similar with a header row of label, pixel1,pixel2….pixel784 which represent a single 28x28 pixel image with grayscale values between 0-255. The original hand gesture image data represented multiple users repeating the gesture against different backgrounds. The Sign Language MNIST data came from greatly extending the small number (1704) of the color images included as not cropped around the hand region of interest. 

Source: https://www.kaggle.com/datamunge/sign-language-mnist



