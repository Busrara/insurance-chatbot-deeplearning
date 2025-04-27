# insurance-chatbot-deeplearning

A smart chatbot designed for insurance companies to solve customer inquiries using deep learning and natural language processing.

## Features

- **Intelligent Intent Recognition**: Uses a neural network to classify customer queries into 14 different insurance-specific intents.
- **Natural Language Processing**: Implements NLTK for text tokenization and lemmatization.
- **High Accuracy**: Achieves 98.66% accuracy on intent classification.
- **Insurance Domain Knowledge**: Pre-configured with comprehensive insurance intents.
- **Performance Visualization**: Includes tools to visualize model accuracy, loss, and intent distribution.

## Technical Components

- Deep learning model with TensorFlow.
- Natural language processing with NLTK.
- Training visualization with Matplotlib.
- Custom intent classification system.

## How It Works

1. The chatbot processes user input using natural language processing techniques.
2. A deep learning model classifies the input into one of the pre-defined insurance intents.
3. The system selects an appropriate response from the response pool for that intent.
4. Performance metrics are tracked and visualized to ensure optimal performance.

## Installation

```bash
# Clone the repository
git clone https://github.com/Busrara/insurance-chatbot-deeplearning.git
cd insurance-chatbot-deeplearning

# Install dependencies
pip install -r requirements.txt

# Run the chatbot
python chatbot.py
