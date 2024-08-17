# Udacity Generative AI Nanodegree Projects

This repository contains assignments and projects completed as part of the [Udacity Generative AI Nanodegree](https://https://www.udacity.com/course/generative-ai--nd608). The projects focus on applying generative AI techniques, including lightweight fine-tuning and building custom AI solutions.

## Project Overview

### 1. **Lightweight Fine-Tuning**
   - **Description**: This project focuses on the fine-tuning of pre-trained models with a small dataset to adapt the model for a specific task. It demonstrates how to leverage transfer learning to optimize performance while minimizing computational resources and time.
   - **Technologies Used**: 
     - Python
     - PyTorch/TensorFlow
     - Hugging Face Transformers
   - **Key Concepts**:
     - Transfer learning
     - Model fine-tuning
     - Efficient training techniques
   - **Status**: Complete

### 2. **Custom Chatbot**
   - **Description**: This project involves creating a custom chatbot tailored to specific needs or use cases. It involves training a conversational model, integrating it with an interface, and customizing responses for a more personalized experience.
   - **Technologies Used**:
     - Python
     - NLP (Natural Language Processing)
     - OpenAI GPT models
   - **Key Concepts**:
     - Conversational AI
     - Model customization
     - User interaction design
   - **Folder**: `custom_chatbot`
   - **Status**: Complete

  ### 3. **AI Photo Editing with Inpainting**
   - **Description**: This project involves building an application that allows users to modify images by changing the background or subject. Users can upload an image, select the main object, and use the Segment Anything Model (SAM) to create a mask. After finalizing the mask, users provide a text description for a new background or subject. The app then uses a text-to-image diffusion model to generate and display the updated image. This tool can be used for tasks such as swapping backgrounds, changing subjects, or removing objects.
   - **Technologies Used**:
     - Python
     - Image processing models (SAM, text-to-image diffusion models)
   - **Key Concepts**:
     - Image segmentation
     - Text-to-image generation
     - Interactive image editing
   - **Folder**: `AI Photo Editing with Inpainting`
   - **Status**: Complete

### 4. **HomeMatch - Personalized Real Estate Listings**
   - **Description**: HomeMatch transforms the real estate search into a personalized experience by matching property listings with individual buyer preferences using advanced Large Language Models (LLMs) and vector databases. It creates tailored property descriptions based on user inputs, enhancing the property search process.
   - **Key Features**:
     - **Understanding Buyer Preferences**: Buyers input specific requirements like location, property type, budget, and amenities. HomeMatch uses LLMs to interpret these preferences.
     - **Integrating with a Vector Database**: Connects to a vector database to store and match property listings based on buyer preferences.
     - **Personalized Listing Description Generation**: Generates descriptions emphasizing aspects most relevant to the buyer’s preferences.
     - **Listing Presentation**: Outputs detailed, personalized property listings to engage and satisfy buyers.
   - **Technologies Used**:
     - Python
     - LLMs
     - Vector databases
   - **Folder**: `HomeMatch`
   - **Status**: In Progress

## Getting Started

### Prerequisites
- Python 3.x
- Virtual Environment (optional but recommended)
- Required Python libraries (see `requirements.txt`) (or edit as per your requirement)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/RitvijSaxena/udacity-gen-ai-nanodegree.git
   ```
2. Navigate to the project directory:
   ```bash
   cd udacity-gen-ai-nanodegree
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Projects

- **Lightweight Fine-Tuning**:
  - Navigate to the `LightWeightFineTuning.ipynb` notebook:
  - Run the fine-tuning script

- **Custom Chatbot**:
  - Navigate to the `customchatbot` directory:
    ```bash
    cd custom_chatbot
    ```
  - Run the `project.ipynb` notebook

- **AI Photo Editing with Inpainting**:
  - Navigate to the `AI Photo Editing with Inpainting` directory:
    ```bash
    cd AI Photo Editing with Inpainting
    ```
  - Run the `starter.ipynb` notebook

- **Homematch**
  - Navigate to the `HomeMatch` directory:
  ```bash
  cd HomeMatch
  ```
  - Run the `HomeMatch.ipynb` notebook

## Contributing

Contributions are welcome! Please fork this repository, create a new branch, and submit a pull request with your changes. Ensure your code adheres to the project's coding standards and is well-documented.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or need further assistance, feel free to reach out via [GitHub Issues](https://github.com/RitvijSaxena/udacity-gen-ai-nanodegree/issues).