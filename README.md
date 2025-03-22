# Plagiarism Detection Tool

## Overview
A comprehensive plagiarism detection tool that offers two main functionalities:
1. Web-based text similarity checking against internet sources
2. File-to-file plagiarism detection using KMP (Knuth-Morris-Pratt) algorithm

## Features

### Web Content Similarity Detection
- Input text analysis through a user-friendly web interface
- Advanced text formatting for optimal search query construction
- Google search integration using the googlesearch package
- Highlighted display of similar content found online
- Percentage calculation of similarity
- Detailed report generation showing:
  - Similar words found online
  - Source websites
  - Percentage of content copied from each source

### File Comparison
- Upload and compare two documents for similarity
- KMP algorithm implementation for efficient string matching
- Detailed similarity percentage calculation
- Highlighted display of matching content

## Tech Stack
- HTML, CSS, Bootstrap for frontend
- Python backend for text processing
- googlesearch package for web queries
- Custom implementation of KMP algorithm

## Live Demo
Try the application: [Plagiarism Detection Tool](https://your-live-link-here)

## Installation and Setup
```bash
# Clone the repository
git clone https://github.com/your-username/plagiarism-detection.git

# Navigate to project directory
cd plagiarism-detection

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

## Usage
### Web Content Check
1. Enter or paste text in the input box
2. Click "Check Plagiarism"
3. View highlighted similar content
4. Check similarity percentage
5. Generate detailed report

### File Comparison
1. Upload two files using the file selection interface
2. Click "Compare Files"
3. View similarity percentage and matching content

## Future Enhancements
- PDF and document format support
- API integration for third-party applications
- Improved accuracy through machine learning
- Bulk file processing

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
