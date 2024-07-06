
# KilterGAN

KilterGAN is a Generative Adversarial Network (GAN) designed to create climbing problems for kilter boards. This repository contains the necessary notebooks for data preparation, exploratory data analysis, GAN model training, and classification.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
  - [Prepare Data](#prepare-data)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Model Training](#model-training)
  - [Classification](#classification)
- [Datasets](#datasets)
- [Contributing](#contributing)
- [License](#license)

## Installation

Clone this repository to your local machine:

\`\`\`bash
git clone https://github.com/yourusername/KilterGAN.git
\`\`\`

Navigate to the project directory:

\`\`\`bash
cd KilterGAN
\`\`\`

Install the required dependencies:

\`\`\`bash
pip install -r requirements.txt
\`\`\`

## Usage

### Prepare Data

The \`Prepare_Data.ipynb\` notebook is used to prepare data from Kilter app screenshots.

### Exploratory Data Analysis

The \`KilterGAN_EDA.ipynb\` notebook contains exploratory data analysis to understand the data better.

### Model Training

The \`KilterGAN_Models_and_Training.ipynb\` notebook is the main notebook for training the GAN models.

### Classification

The \`KilterGAN_Classifier.ipynb\` notebook is used for classification tasks using a Convolutional Neural Network (CNN).

## Datasets

- **VDifficult.zip**: Contains datasets V4, V5, and V6.
- **VEasy.zip**: Contains the VEasy dataset.
- **test_images_vall.zip**: Contains test images for the VAll dataset.
- **test_images_veasy.zip**: Contains test images for the VEasy dataset.
- **test_images_vhard.zip**: Contains test images for the VHard dataset.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for review.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
