# Question Duplication Detection for Forums

## Introduction
This project focuses on identifying duplicate questions in online forums such as Quora, StackOverflow, and Yahoo Answers, with the aim to reduce redundancy and improve the efficiency of answering queries. By detecting semantically equivalent questions, the system retrieves and displays already available answers, thus saving significant search time.

## Technologies Used
- Python
- Spacy (with GLoVE model for word embeddings)
- Beautiful Soup for web scraping
- Pandas for data manipulation
- NLTK for natural language processing tasks

## Features
- Detection of duplicate questions using semantic similarity.
- Integration of word embeddings via the GLoVE method to understand contextual meanings of words.
- Use of cosine similarity measures to determine the closeness of question pairs.
- Storage and retrieval of question-answer pairs to/from a structured dataset.

## Getting Started

### Prerequisites
- Python 3.6+
- Spacy, Beautiful Soup, Pandas, NLTK
- An IDE like PyCharm or a text editor such as Sublime Text or VS Code

### Installation
1. Clone the repository:
```bash
git clone https://github.com/your-username/question-duplication-detection.git
```

2. Navigate into the project directory:
```bash
cd folder-name
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

### Usage
Run the application by running individual cells in ipynb or export the ipynb as a .py file to run with:
```bash 
python3 filename.py
```

Navigate through the application to upload questions and view results.

## Contributing
Contributions to enhance the functionality of this project are welcome. For major changes, please open an issue first to discuss what you would like to change. Please ensure to update tests as appropriate.


## Acknowledgements
- Palakorn Achananuparp, Xiaohua Hu for their insights on utilizing sentence similarity.
- The developers of the GLoVE model for providing an excellent tool for word representation.
- The open-source community for continuous support and inspiration.

## Contact
For any feedback or queries, please reach out to us at:
- Email: ratantejaswi@gmail.com
- LinkedIn: [Ratan Tejaswi Vadapalli](https://www.linkedin.com/in/ratan-tejaswi-vadapalli/)
