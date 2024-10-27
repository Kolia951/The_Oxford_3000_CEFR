# The Oxford 3000™ by CEFR level
This repository contains a text file of the Oxford 3000 grouped by CEFR level.

CEFR is "Common European Framework of Reference for Languages"

The data is derived from [HERE](https://www.oxfordlearnersdictionaries.com/external/pdf/wordlists/oxford-3000-5000/The_Oxford_3000_by_CEFR_level.pdf)

## Contents
The repository contains the following items:
1. `package.txt` - this is a .txt file that contains the JSON serialized string of the Oxford 3000 grouped by CEFR level.
2. `The_Oxford_3000_by_CEFR_level.pdf` - this is an initial file for package.txt.

## Data Format
The data in `package.txt` is formatted as a JSON serialized string. Each word is grouped by its CEFR level. This format allows you to easily search, filter, and parse the data based on your needs. Please note that the file contains only "A1", "A2", "B1" and "B2" levels.

The data in the file follows this general structure:

```json
{
  "A1": ["word1", "word2"],
  "A2": ["word3", "word4"],
  "B1": ["word5", "word6"],
  "B2": ["word7", "word8"],
}
```
Lists of words for every level have been sorted in alphabetical order.

## How to Use
You can use this data in your programming projects to generate language learning exercises or try to define (approximately) the level of English of a user.
Just clone the repository or make a fork.
