# CLIP: Connecting Text to Images with Multimodal Learning

This repository contains a blog-style Jupyter Notebook that explains the CLIP model (Contrastive Language–Image Pretraining) developed by OpenAI. The notebook explores CLIP’s architecture, training approach, strengths, and applications in the field of multimodal learning.

##  Contents

-  Introduction and Motivation
-  Connection to Past Work in Multimodal AI
-  Key Learnings from CLIP
-  Code Demos using HuggingFace Transformers
-  Reflections and Future Directions
-  References and Resources

##  What is CLIP?

CLIP is a powerful model trained on 400M image-text pairs that learns to match images with their textual descriptions. Unlike traditional supervised models, CLIP can perform tasks without any task-specific training—thanks to zero-shot capabilities enabled by contrastive learning.

##  Jupyter Notebook

The notebook includes:

- An overview of CLIP and multimodal learning
- Code demos using the openai/clip-vit-base-patch32 model
- Example: predicting image labels via similarity with natural language prompts
- Markdown explanations and diagrams to illustrate core ideas

##  Requirements

To run the notebook, install the required packages:

```bash
pip install transformers torch pillow
