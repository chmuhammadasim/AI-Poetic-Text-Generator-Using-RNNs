## AI Poetic Text Generator Using RNNs

This repository contains a Python implementation of an AI Poetic Text Generator using Recurrent Neural Networks (RNNs). The generator utilizes Long Short-Term Memory (LSTM) networks, a type of RNN suitable for sequential data like text, to produce expressive and poetic text reminiscent of human creativity.

### Dataset
The model is trained on a subset of Shakespearean text obtained from the TensorFlow dataset. The dataset has been preprocessed to extract a portion of the text suitable for training the generator.

### Dependencies
- TensorFlow 2.x
- NumPy

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/poetic-text-generator.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
1. Run the `poetic_text_generator.py` script to train the model and generate poetic text.
   ```bash
   python poetic_text_generator.py
   ```
2. Adjust the hyperparameters in the script to customize the training process and the generated text:
   - `SEQ_LENGTH`: Length of input sequences for the LSTM model.
   - `STEP_SIZE`: Step size for extracting sequences from the text data.
   - `epochs`: Number of training epochs for the model.
   - `temperature`: Temperature parameter for controlling the creativity of the generated text.

### Generated Text
The generated poetic text will be displayed in the console, with variations based on the temperature parameter.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments
- This project is inspired by the work of creative text generation using neural networks.
- The TensorFlow team for providing the Shakespeare dataset and valuable resources for deep learning.

### Disclaimer
This project is for educational and research purposes only. The generated text may not always be grammatically correct or coherent. Use discretion when interpreting the output.
