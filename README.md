# VLM-for-Scene-Recognition-in-AVs
This project uses VLM CLIP Embeddings for recognizing and finding similarity between images and texts.

# Contrastive Language-Image Pretraining (CLIP)
CLIP is a technique developed by OpenAI that trains an image encoder and a text encoder simultaneously to learn a shared semantic space, enabling zero-shot image classification and other vision-language tasks. It works by using contrastive objective to pull related image-text pairs closer together in this shared space while pushing urelated pairs further apart. After being trained on massive internet-scale datasets of images and their associated text, CLIP can generalize to new classification tasks without needing specific fine-tuning for them.

This project focuses on building an image-classifier model using OpenAI's CLIP to improve the safety features in Autonomous Vehicle perception. In extensions of these projects, the aim is to develop interactive models and scene recognition and classification.

# Plot Images
This utility function plots images with their labels.

<img width="629" height="148" alt="image" src="https://github.com/user-attachments/assets/e7dba844-5773-4c41-b12c-776ec403ea21" />

# CLIP Image-Text Similarity Heatmap
The heatmap below represents an important relation where a baby is classified as a pedestrian since, in the image the baby is crossing the road, hence improving the safety of the road users in any condition.

<img width="653" height="547" alt="image" src="https://github.com/user-attachments/assets/819b155c-1e2e-4e02-be1e-4db121f6e8c4" />

# Zero-Shot Image Classification using CLIP 
The code classifies the new image introduced without any prior training with 98% accuracy

<img width="275" height="183" alt="image" src="https://github.com/user-attachments/assets/41e9cbd0-fb20-44d9-a09f-3c43b7e2e7e7" />

Output:

Probability of car: 0.005628455430269241

Probability of truck: 0.9894397854804993

Probability of bus: 0.004394009709358215

Probability of cycle: 0.0005377031047828496

Predicted Label: truck

# Scene captioning with QWEN 2.5 VL

The model gives a description of the image in Natural Language

<img width="515" height="372" alt="image" src="https://github.com/user-attachments/assets/9fa4e5ef-a8df-4dbf-af71-a81562af1c3c" />


Output

"The image depicts a bustling urban scene, likely from a major city known for its vibrant nightlife
and commercial activity. The primary focus is on a busy street corner with several key elements:  1.
**Taxi**: In the foreground, there is a yellow taxi cab, which is a common sight in many cities"


