**Features**
1. **clean_text**

Reads input.txt

Removes special characters

Converts text into clean, one-word-per-line format

Generates clean_text output file

2.**filter_duplicates**

Reads cleaned words

Removes duplicate entries

Produces filtered.txt

3.**sort_stored**
(Optional – only used if you want sorted storage)

Sorts words alphabetically

Outputs sorted results to stored.txt

4. **update_stored**

Compares new words with existing stored words

Adds only missing new words

Ensures your main dictionary stays updated without duplication

**Build Instructions**


make


This compiles all utilities:

clean_text

filter_duplicates

update_stored

sort_stored (if needed)

To clean all build files:

make clean

Purpose of This Project

This project helps you:

Maintain a personal or project-specific word list

Automatically clean and prepare text

Avoid duplicates

Keep an ever-growing dictionary efficiently

Use wordlists for NLP, search, linguistics, or vocabulary building

**Future Improvements & Development Roadmap**

To improve stability, performance, and usability, the project will evolve with the following planned updates:

1. **Improve Code Quality & Stability**

Refactor all .cpp files into modular, reusable functions

Add error handling for file operations (missing files, permission errors, empty input, etc.)

Add unit tests to validate each step (cleaning, filtering, updating)

Improve performance for large files using buffer-based processing instead of line-by-line loops

Add memory-safety improvements and eliminate edge-case crashes

2. **Add Logging and Debug Support**

Add verbose logging (--verbose option)

Add debug mode to help track issues in text processing

Add colored terminal output for easier readability

