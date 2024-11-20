# Neural Style Transfer  

A neural style transfer system that blends the content of one image with the artistic style of another using TensorFlow and a pre-trained VGG19 model. The project showcases key concepts in deep learning, such as content and style loss, Gram matrix computation, and optimization techniques.

## Features
- Extracts content and style features using the VGG19 model.
- Computes style loss using the Gram matrix representation of image features.
- Combines content and style into a single output image.
- Modular and well-documented code structure.

## Repository Details
- **Notebook File:** `neural_style_transfer.ipynb`
- The system is set to run for **epoch 0 only** due to hardware limitations. Users can adjust the `epochs` parameter for more iterations if their system allows.

## How It Works
1. Preprocesses the input content and style images.
2. Extracts image features using VGG19's convolutional layers.
3. Defines content and style loss functions.
4. Optimizes a randomly initialized image to minimize the combined content and style loss.

## Prerequisites
- Python 3.8 or later
- TensorFlow 2.x
- NumPy
- Matplotlib

## Usage
1. Clone this repository:  
   ```bash
   git clone https://github.com/ahmdmohamedd/neural-style-transfer.git
   ```
2. Navigate to the project directory:  
   ```bash
   cd neural-style-transfer
   ```
3. Open the Jupyter Notebook:  
   ```bash
   jupyter notebook neural_style_transfer.ipynb
   ```
4. Replace `path_to_content_image.jpg` and `path_to_style_image.jpg` with your image paths.  

## Notes
- Due to hardware limitations, this implementation demonstrates the result after **epoch 0**. For improved results, increase the number of epochs if your hardware supports it.

## Output Example (Epoch 0)
The resulting image combines the content structure of the content image with the style patterns of the style image.  
