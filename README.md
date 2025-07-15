CLIP-FairFace Tag2Prompt
This project combines OpenAI's CLIP model with the FairFace image classification model to analyze an image and generate a reverse-engineered prompt that describes its contents. It tags visual attributes such as race, gender, setting, lighting, and the number of people in the image.

This tool is useful for research on algorithmic bias, reverse-prompting, and visual context extraction for generative image workflows.

Features
Detects race and gender using FairFace (if face detected)

Uses CLIP to classify visual context such as setting, lighting, and number of people

Falls back to CLIP for race/gender if FairFace fails or is unavailable

Converts extracted tags into a natural language prompt

Runs locally using PyTorch and Hugging Face models

Supports images from a specified local folder (~/Desktop/AI_IMG_GPT/)

Sample Output
A white male in a hospital setting, under bright light conditions, with one person in frame.
