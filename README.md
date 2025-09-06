
# Regional English Accent Classification using MFCC Vectors

## Overview
**Regional-English-Accent-Classification-using-MFCC-Vectors** is a Python-based machine learning project designed to accurately classify regional Indian English accents using Mel Frequency Cepstral Coefficients (MFCC) vectors. The system currently demonstrates 100% accuracy in identifying Punjabi, Assamese, Telugu, Malayalam, Kashmiri, Kannada, and Bengali English accents. The project aims to support organizations in categorizing speakers by English accent for tailored applications, such as recruitment and client-facing roles.

## Features
- **Accurate accent classification:** Achieves 100% accuracy for seven major Indian regional accents.
- **MFCC vector extraction:** Utilizes MFCC feature vectors for robust audio analysis.
- **Python implementation:** Written entirely in Python for easy customization and extensibility.
- **Business applications:** Supports HR, analytics, and other domains requiring accent-based categorization.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/25Ray07/Regional-English-Accent-Classification-using-MFCC-Vectors.git
   cd Regional-English-Accent-Classification-using-MFCC-Vectors
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   *(Add a `requirements.txt` file with all necessary packages if not present.)*

## Usage

1. **Prepare your dataset:**  
   Ensure your English speech samples are organized by region (Punjabi, Assamese, Telugu, etc.).

2. **Run the classification script:**
   ```bash
   python classify_accent.py --input /path/to/audio/files
   ```
   *(Adapt the script and command as per your project structure and filenames.)*

3. **Interpret the results:**  
   The output will indicate the detected regional accent for each sample.

## Project Structure

```
Regional-English-Accent-Classification-using-MFCC-Vectors/
├── classify_accent.py      # Main script for classification
├── utils.py                # Utilities for MFCC extraction and processing
├── data/                   # Directory for datasets
├── models/                 # Saved models and weights
└── README.md               # Project documentation
```

## Contributing

Contributions are welcome!
- Fork the repository
- Create your feature branch: `git checkout -b feature/YourFeature`
- Commit your changes: `git commit -am 'Add new feature'`
- Push to the branch: `git push origin feature/YourFeature`
- Create a pull request

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Contact

For questions, feedback, or collaboration opportunities, open an issue or contact the repository owner via GitHub.
