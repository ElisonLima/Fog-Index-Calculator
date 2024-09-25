# Fog-Index-Calculator
This repository contains a Python script that calculates the Gunning Fog Index for texts 

## What is the Fog Index?

The Gunning Fog Index, or simply Fog Index, is a readability measure for written text. Developed by Robert Gunning in 1952, this index estimates the number of years of formal education needed to understand a text on first reading.

## Features

- Calculates the Fog Index for English texts
- Accepts text input via file or directly through the console
- Provides an interpretation of the obtained score

## Requirements

- Python 3.6+
- NLTK (Natural Language Toolkit)

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-username/fog-index-calculator.git
   ```

2. Navigate to the project directory:
   ```
   cd fog-index-calculator
   ```

3. Install the dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

Run the main script:

```
python fog_index.py
```

Follow the console instructions to enter the text or the path of the file you want to analyze.

## Example Output

```
Analyzed text: "The Gunning Fog Index measures the readability of English writing..."

Number of sentences: 5
Number of words: 50
Number of complex words: 10

Fog Index: 12.4

Interpretation: This text is suitable for readers with a high school diploma or higher education.
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact

If you have any questions or suggestions, please open an issue in this repository or contact us at: your-email@example.com.