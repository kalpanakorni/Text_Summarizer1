# AI Text Summarizer

## Project Description

AI Text Summarizer is a web-based application developed to generate concise summaries from user-provided text. The application provides multiple text summarization approaches and allows the user to control the length and number of sentences included in the generated summary.

The system processes the input text, identifies important sentences based on the selected method, and presents the generated summary along with basic text statistics.

## Features

* Accepts text entered by the user for summarization.
* Provides three summarization methods:

  * TF-IDF Weighting
  * Query-Based Summarization
  * Information Extraction
* Allows the user to specify the desired summary length.
* Allows the maximum number of sentences in the summary to be adjusted.
* Displays the original word count.
* Displays the summary word count.
* Calculates the compression percentage.
* Displays the number of sentences used in the summary.
* Provides a responsive interface for different screen sizes.

## Summarization Methods

### TF-IDF Weighting

The TF-IDF method calculates the importance of words within the input text and uses the resulting scores to determine the importance of individual sentences. The sentences with higher scores are selected to form the summary.

### Query-Based Summarization

This method generates a summary according to a query provided by the user. Sentences are scored based on their relevance to the query along with their TF-IDF scores.

### Information Extraction

The information extraction method assigns scores to sentences based on basic subject, verb, and object patterns. Sentence position is also considered while determining the importance of a sentence.

## Technologies Used

* HTML5
* CSS3
* JavaScript
* TF-IDF
* Natural Language Processing concepts

## Project Structure

```text
AI-Text-Summarizer/
│
├── index.html
└── README.md
```

The application interface, styling, and summarization logic are implemented in the HTML file.

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/AI-Text-Summarizer.git
```

2. Open the project directory.

```bash
cd AI-Text-Summarizer
```

3. Open `index.html` in a web browser.

Alternatively, the project can be opened using the Live Server extension in Visual Studio Code.

## How to Use

1. Enter the text that needs to be summarized.
2. Select one of the available summarization methods.
3. If **Query-Based Summarization** is selected, enter the required query.
4. Set the summary length and maximum number of sentences.
5. Select **Generate Summary**.
6. The generated summary and its corresponding statistics will be displayed.

## Output

The application displays the following information after processing the input:

* Original Words
* Summary Words
* Compression Percentage
* Sentences Used
* <img width="1336" height="802" alt="Screenshot 2026-08-15 213649" src="https://github.com/user-attachments/assets/e34b2aa1-ccb9-4e30-9ef7-e11dd67569db" />
<img width="992" height="901" alt="Screenshot 2026-08-15 213748" src="https://github.com/user-attachments/assets/97a1a496-b7a5-45d5-91b3-318346542c8d" />



The statistics are calculated from the original text and the generated summary.

## Author

**Kalpana Korni**

Developed as part of an internship project at **CodeTech IT Solutions**.

## License

This project is intended for educational and project demonstration purposes.
