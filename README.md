# AquaLeaf

**AquaLeaf** is an AI-powered computer vision project designed to support environmental health and sustainability. Using **TensorFlow** and **OpenCV**, the system analyzes images to detect fires and identify targeted plant diseases.

The project was created in response to the environmental damage and public-safety challenges highlighted by the **California Palisades Fire**. AquaLeaf explores how machine learning can help communities identify environmental threats earlier and support faster, more informed responses.

## Recognition

AquaLeaf won an **AI4SG competition**. The project focused on using artificial intelligence for social good, with an emphasis on sustainability, wildfire awareness, plant health, and environmental resilience.

## Key Capabilities

- **Fire detection:** Uses computer vision to identify visual indicators of fire in images.
- **Plant disease detection:** Classifies selected plant-health conditions from visual features in plant images.
- **Image preprocessing:** Uses OpenCV to prepare and transform images before model inference.
- **Machine learning classification:** Uses TensorFlow to train and run the computer vision model.
- **Environmental-health focus:** Connects AI development with wildfire awareness, ecological protection, and community safety.

## Technology Stack

- **Python** — application and model-development language
- **TensorFlow** — machine learning and neural-network framework
- **OpenCV** — image processing and computer vision utilities

## How It Works

```text
Input image
     ↓
OpenCV preprocessing
     ↓
TensorFlow computer vision model
     ↓
Fire or plant-disease prediction
     ↓
Result for environmental monitoring and awareness
```

The image is first prepared through preprocessing steps such as resizing and normalization. The processed image is then passed to the TensorFlow model, which evaluates visual patterns and returns a prediction for the categories included in the trained dataset.

## Project Motivation

Wildfires and plant diseases can cause lasting damage to communities, ecosystems, agriculture, and public health. AquaLeaf was developed to demonstrate how accessible AI tools can support earlier awareness of environmental threats and contribute to more sustainable, data-informed decision-making.

## Potential Applications

- Supporting wildfire monitoring and environmental awareness
- Helping identify plant-health concerns at an early stage
- Assisting sustainability and conservation initiatives
- Providing a foundation for future environmental-monitoring tools

## Limitations

AquaLeaf is a research and competition project, not a replacement for emergency services, professional fire detection systems, agricultural experts, or environmental agencies. Model performance depends on the quality, diversity, and labeling of the training data. Predictions should be verified by qualified professionals before being used for safety-critical or agricultural decisions.

## Future Improvements

- Expand the training dataset across different lighting, weather, plant, and wildfire conditions
- Add confidence scores and clearer explanations for predictions
- Improve generalization to new regions and plant species
- Develop a real-time monitoring interface
- Evaluate the model with precision, recall, F1 score, and confusion matrices
- Explore deployment on mobile or edge-computing devices

## Project Impact

AquaLeaf demonstrates how machine learning and computer vision can be applied to real-world environmental challenges. By combining TensorFlow with OpenCV, the project turns visual information into actionable environmental insight while promoting the use of AI for sustainability and social good.

## Author

Created by **Ryan Morla**.
