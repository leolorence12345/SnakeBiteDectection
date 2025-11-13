# Snakebite Identification System

**A System For Snake Bite Imaging And Classification**  
*Pending Patent Approval*

## Project Overview

Snakebite envenomation is a serious public health challenge, particularly in rural areas with limited access to timely medical care. Accurate snake species identification is critical for administering the correct antivenom, as misidentification can lead to ineffective treatment. This project developed a predictive model that integrates epidemiological data, machine learning, and bite mark imaging to accurately identify the snake species responsible for envenomation.

## Key Achievements

- **91% accuracy** in snakebite identification using YOLOv8 on synthetic and clinical bite mark images
- **1,000+ synthetic bite mark scenarios** constructed, improving dataset diversity and model performance
- **Hybrid ML model** architected combining image and epidemiological data, validated on **50 real hospital cases**

## Project Details

### Data Acquisition

Data for this project was acquired through a collaboration with **Monosha Biotech**, a serpentarium and venom lab. Monosha Biotech provided expert knowledge on the probabilities associated with different features, which were organized into an Associated Probability Matrix. This matrix represented the likelihood of a specific snake species being responsible for a bite based on factors like location and symptoms.

### Bite Mark Imaging

Images were preprocessed through auto-orientation, resizing, and contrast adjustments to enhance clarity, while adaptive equalization highlighted subtle details. Augmentation techniques, like flips and rotations, were applied to introduce real-world variability and strengthen the model's generalization. The **YOLOv8 deep learning model** was used to detect bite marks and assess envenomation severity, contributing to the prediction of the snake species involved.

### Synthetic Data Generation

Due to the scarcity of real-world snakebite data, synthetic data was generated to bridge this gap. This dataset simulated epidemiological factors, including location, time of day, and symptoms, with a cross-covariance matrix capturing dependencies to maintain real-world correlations. By replicating these patterns, the synthetic data expanded the model's training scenarios, enhancing its predictive accuracy and robustness.

### Model Training

The predictive model was trained using both real and synthetic data, incorporating key features like location, time of bite, symptoms, and bite mark images. After optimizing the model, it achieved strong performance metrics, demonstrating its effectiveness in accurately predicting the snake species responsible for a bite. This approach significantly improved predictive accuracy, combining epidemiological data and imaging for real-world applications.

## Results

The results of the predictive model showcased its effectiveness in accurately identifying snake species based on a combination of epidemiological data and bite mark imaging. By integrating real and synthetic data, the model was able to predict the responsible species with a high degree of accuracy, making it a valuable tool for improving snakebite management. The model was tested and validated through many real-world case studies demonstrating its practical application and robustness.

### Case Study 1: Russell's Viper Bite

The model accurately predicted a Russell's viper bite, aligning with clinical observations, despite the absence of typical envenomation symptoms like swelling and pain.

**Clinical assessment revealed:**
- Absence of typical symptoms of venomous snakebite
- No pain, burning, or discoloration at the bite site
- No local swelling or blistering
- No systemic symptoms of envenomation (drowsiness, respiratory difficulty, abdominal pain, ptosis, swallowing issues, chest and throat burning, hemorrhage, or paralysis)

### Case Study 2: Spectacled Cobra Bite

A bite showing no local symptoms but distinct bite marks was accurately identified as caused by a Spectacled cobra, consistent with the ground truth.

**Clinical assessment revealed:**
- Two distinct bite marks observed on the hand
- No local symptoms of envenomation present
- Absence of pain, burning, swelling, or skin discoloration
- No systemic signs of envenomation
- Incident occurred during heavy rain

## Patent Documentation

<iframe src="PatentFiledForm.pdf" width="100%" height="800px" style="border: 1px solid #ccc; border-radius: 5px;"></iframe>

**Direct Link**: [View/Download PDF](PatentFiledForm.pdf)

## Additional Resources

- **Project Website**: [https://sites.google.com/view/leolorence/patent](https://sites.google.com/view/leolorence/patent)
- **Collaboration Partner**: Monosha Biotech (Serpentarium and Venom Lab)

## Code Availability

**Note:** The source code for this project cannot be shared at this point due to pending patent approval. Once the patent process is complete, code availability will be reassessed.

## Research Impact

This project addresses a critical gap in snakebite management, particularly in resource-limited settings where expert identification may not be readily available. The combination of deep learning image analysis with epidemiological data provides a robust, practical solution for accurate snake species identification, potentially saving lives through timely and correct antivenom administration.

## Technical Specifications

- **Model Architecture**: YOLOv8 for bite mark detection and classification
- **Data Sources**: 
  - Real clinical cases from hospital collaborations
  - Synthetic data generation for dataset augmentation
  - Expert knowledge from Monosha Biotech
- **Validation**: 50 real-world hospital case studies
- **Performance**: 91% accuracy in snake species identification
- **Dataset Size**: 1,000+ synthetic scenarios + real clinical data

## Acknowledgments

- **Monosha Biotech** for providing expert knowledge and collaboration
- Hospital partners for providing real-world case data
- Research team and advisors

## Contact

For inquiries about this project, please visit the [project website](https://sites.google.com/view/leolorence/patent) or contact through the provided channels.

---

**Status**: Pending Patent Approval  
**Last Updated**: 2024
