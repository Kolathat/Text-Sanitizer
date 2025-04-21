# Text Sanitizer & Analyzer

A flexible and extensible Python command-line tool for sanitizing, analyzing, and reporting on text data from various sources. This project is designed with modularity and best practices in mind, making it easy to adapt for different text processing or ETL scenarios.

Key Features:
- Flexible Input: Read text from a file, direct string, or built-in sample data.
- Configurable Output: Print results to the console or write to a file.
- Text Sanitization: Convert text to lowercase, replace tabs with custom markers, and handle corrupted or mixed-format data.
  
- Detailed Statistics: Generate both basic and enhanced statistics, including:
  - Character frequencies (alphabetic, numeric, whitespace, special)
  - Word and line counts
  - Average word length
  - Non-empty line count

- Extensible Architecture: Easily extend with new sanitization or statistics modules using abstract base classes.
- Logging & Error Handling: Comprehensive logging for all steps and robust error handling for production use.
- Configurable via CLI or JSON: Supports command-line arguments and external configuration files.

**How to Use:**
  Run from the command line with options for source, target, and config:

  python text_sanitizer.py --source input.txt --target output.txt

- If no source is provided, sample data will be used.
- Output includes both the sanitized text and a detailed statistics report.

**Possible Extensions:**
- Add custom sanitization rules (e.g., stopword removal, stemming)
- Integrate with NLP libraries for advanced text analytics
- Support for batch processing or streaming data



<img width="361" alt="image" src="https://github.com/user-attachments/assets/2def7a64-e732-4b4c-a6ca-56d71e00787c" />
