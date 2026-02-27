# MEsohEstimator

A minimal deep learning-based State of Health (SoH) prediction tool for batteries, with guidance for using wide-range real-world datasets.

## Features
- Deep learning model for SoH prediction using Keras/TensorFlow
- Example with synthetic data for quick testing
- References to public battery datasets for real-world applications
- Easily replaceable data loading section for your own experiments

## Getting Started

### Prerequisites
- Python 3.7+
- pip
- Recommended: virtual environment (venv, conda, etc.)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/koneke55/MEsohEstimator.git
   cd MEsohEstimator
   ```
2. Install dependencies:
   ```bash
   pip install numpy scikit-learn tensorflow
   ```

### Usage
1. Open `mesoh.ipynb` in Jupyter or VS Code.
2. Run the notebook to see a minimal deep learning SoH prediction example.
3. For real-world use, download a dataset from one of the sources below and replace the synthetic data section with your own data loading and preprocessing code.

## Public Battery Datasets
- [NASA Battery Data Set](https://www.nasa.gov/content/prognostics-center-of-excellence-data-set-repository)
- [CALCE Battery Data](https://web.calce.umd.edu/batteries/data.htm)
- [Oxford Battery Degradation Dataset](https://ora.ox.ac.uk/objects/uuid:1b9c6c90-6b8a-4c3a-a8b3-9b8b7b8b7b8b)

## Project Structure
- `mesoh.ipynb` — Main notebook with code and instructions

## License
This project is licensed under the MIT License.

## Author
- koneke55 (20btrmt034@jainuniversity.ac.in)


