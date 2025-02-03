# Stance Detection, Keyword Extraction, and Topic Modeling on YouTube Comments

This project focuses on analyzing YouTube comments to detect stances (Pro-Palestine, Pro-Israel, or Neutral) using a fine-tuned BERT model. Additionally, keyword extraction is performed using KBERT, and topic modeling is implemented using BeTopic.

## Features

- **Stance Detection**: Fine-tuned BERT model to classify YouTube comments into three categories:
  - Pro-Palestine
  - Pro-Israel
  - Neutral

- **Keyword Extraction**: Utilized KBERT to extract meaningful keywords from the comments.

- **Topic Modeling**: Applied BeTopic to identify and analyze prevalent topics within the dataset.

## Technologies Used

### Machine Learning Frameworks
- **BERT**: For stance detection and fine-tuning
- **KBERT**: For keyword extraction
- **BeTopic**: For topic modeling

### Programming and Libraries
- **Python**: Primary programming language
- **Hugging Face Transformers**: For BERT implementation
- **Other Libraries**:
  - Pandas
  - NumPy
  - Scikit-learn

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/youtube-comments-analysis.git

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install required dependencies
pip install -r requirements.txt
```

## Usage

```python
# Example usage (placeholder - replace with actual code)
from bert_stance_detector import StanceDetector

# Initialize the stance detector
detector = StanceDetector()

# Analyze a YouTube comment
comment = "Some example comment about the conflict"
stance = detector.predict_stance(comment)
print(f"Detected Stance: {stance}")
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[Specify your license here, e.g., MIT License]
