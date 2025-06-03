
# 📝 Resume Parser

A powerful and easy-to-use Resume Parser built with Python to extract relevant information from resumes in `.pdf` or `.docx` format. This tool helps automate the candidate screening process by parsing resumes and extracting structured information like name, email, phone, skills, education, and more.

## 🚀 Features

- Upload and parse resumes in PDF or DOCX formats.
- Extract key candidate details:
  - Name
  - Email
  - Phone Number
  - Skills
  - Education
  - Experience
- Simple and intuitive interface using Jupyter Notebook.
- Based on NLP and regex techniques for robust text extraction.

## 📁 Project Structure

```bash
.
├── Resume_parser.ipynb   # Jupyter Notebook for resume parsing
├── sample_resumes/       # Directory to store sample resumes (optional)
└── README.md             # Project documentation
```

## 🛠️ Dependencies

Make sure to install the required Python libraries:

```bash
pip install pandas numpy nltk spacy python-docx PyPDF2
```

Also, download the spaCy English language model if not already available:

```bash
python -m spacy download en_core_web_sm
```

## 📌 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/resume-parser.git
   cd resume-parser
   ```

2. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook Resume_parser.ipynb
   ```

3. Upload a resume and run the cells to extract the desired information.

## 📦 Future Improvements

- Web-based interface with Flask or Streamlit.
- Support for multi-language resume parsing.
- Integration with databases or applicant tracking systems (ATS).
- Export parsed data as JSON or CSV.

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or pull requests to improve this project.
