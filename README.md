# VLM-for-Scene-Recognition-in-AVs
This project uses VLM CLIP Embeddings for recognizing and finding similarity between images and texts.

# Contrastive Language-Image Pretraining (CLIP)
CLIP is a technique developed by OpenAI that trains an image encoder and a text encoder simultaneously to learn a shared semantic space, enabling zero-shot image classification and other vision-language tasks. It works by using contrastive objective to pull related image-text pairs closer together in this shared space while pushing urelated pairs further apart. After being trained on massive internet-scale datasets of images and their associated text, CLIP can generalize to new classification tasks without needing specific fine-tuning for them.

This project focuses on building an image-classifier model using OpenAI's CLIP to improve the safety features in Autonomous Vehicle perception. In extensions of these projects, the aim is to develop interactive models and scene recognition and classification.

# Calculation of Cosine Similarity between Text Embeddings
The image shows a heatmap of Cosine Similarity between Text Embeddings when the code is run.
<img width="596" height="393" alt="image" src="https://github.com/user-attachments/assets/d02c94d4-62ff-4b3e-badd-1f1c9f83db09" />

# Plot Images
This utility function plots images with their labels.

<img width="629" height="148" alt="image" src="https://github.com/user-attachments/assets/e7dba844-5773-4c41-b12c-776ec403ea21" />

# Cosine Similarity between Image Embeddings
<img width="645" height="547" alt="image" src="https://github.com/user-attachments/assets/26ba88be-8923-41d6-a826-3a4ad6ecb604" />

# CLIP Image-Text Similarity Heatmap
The heatmap below represents an important relation where a baby is classified as a pedestrian since, in the image the baby is crossing the road, hence improving the safety of the road users in any condition.

<img width="653" height="547" alt="image" src="https://github.com/user-attachments/assets/819b155c-1e2e-4e02-be1e-4db121f6e8c4" />
