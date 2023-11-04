# Translate-English-Hinglish
## Requirements

Before using the code, you need to install the required libraries. You can do this by running the following commands:

**!pip install nltk**                    # Install the Natural Language Toolkit library.

**!pip install googletrans==4.0.0-rc1**  # Install the googletrans library version 4.0.0-rc1.

The code also requires the 'punkt' and 'averaged_perceptron_tagger' datasets for NLTK, which can be downloaded using:

**nltk.download('punkt')**

**nltk.download('averaged_perceptron_tagger')**
## Code Structure

The code consists of several functions:

**find_nouns(sentence):** This function takes an English sentence as input and returns a list of nouns present in the sentence.

**translate_to_hindi(text):** This function takes an English text as input and uses the Google Translate API to translate it to Hindi.

**replace_nouns_with_english(hindi_sentence, english_sentence, retain_english_nouns=False):** This function replaces nouns in a Hindi sentence with their English counterparts, using the previously translated English nouns. You can choose whether to retain the English nouns in the final sentence with the retain_english_nouns parameter.

## Test function
A test section at the end of the code demonstrates the functionality of the above functions, both for a predefined set of sentences and by taking user input.

You can test the code with predefined sentences or provide your own input.
***Example Usage***

sentences = [
    "Definitely share your feedback in the comment section.",
    "So even if it's a big video, I will clearly mention all the products.",
    "I was waiting for my bag."
]


## Outout Screenshot
![image](https://github.com/naveen7259/Translate-English-Hinglish/assets/108933845/d8a1ce53-6324-4ed5-88d4-d8c83e989747)

