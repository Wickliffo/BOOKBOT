**Bookbot** is a Python-based command-line utility designed for automated text analysis. It serves as a lightweight ETL (Extract, Transform, Load) pipeline that processes large-scale text files—such as classic literature—to extract meaningful statistical insights regarding word counts and character frequency.

## 🚀 Features
*   **Word Counting:** Rapidly quantifies the total word count of any `.txt` file.
*   **Character Frequency Analysis:** Aggregates the occurrence of every alphabetical character, standardized to lowercase for data consistency.
*   **Dynamic Reporting:** Generates a clean, sorted terminal report of character distributions from highest to lowest frequency.
*   **CLI Argument Support:** Accepts dynamic file paths via command-line arguments, allowing for analysis of multiple datasets without code changes.

## 🛠️ Technical Stack
*   **Language:** Python 3.x
*   **Environment:** Developed and tested on Ubuntu Linux (Dell Latitude 7400).
*   **Concepts:** File I/O, Data Aggregation, Dictionary Mapping, System Arguments (`sys.argv`), and Modular Code Architecture.

## 📂 Project Structure
```text
bookbot/
├── books/                  # Raw text datasets (.txt files)
├── main.py                 # Application entry point and orchestrator
├── stats.py                # Analysis logic and data transformation modules
├── .gitignore              # Ensures clean version control
└── README.md               # Project documentation
⚙️ Installation & Usage1. Clone the RepositoryBashgit clone https://github.com/Wickliffo/BOOKBOT.git
cd BOOKBOT
2. Run the AnalysisBashpython3 main.py books/frankenstein.txt
3. Sample OutputPlaintext============ BOOKBOT ============
Analyzing book found at books/frankenstein.txt...
----------- Word Count ----------
Found 75767 total words
--------- Character Count -------
e: 44538
t: 29493
a: 25894
...
============= END ===============
🧠 Learning ObjectivesThis project focuses on Analytical Engineering fundamentals:Memory Management: Handling strings efficiently using with open() context managers.Algorithm Efficiency: Implementing character counting with $O(n)$ complexity using dictionaries.Modularization: Separating logic into distinct modules (main.py vs stats.py).EOF
