**Flashy - Turkish Vocabulary Learning App**
Flashy is an interactive flashcard application designed to help users learn and practice Turkish vocabulary efficiently. It leverages a visually engaging interface and tracks progress dynamically.

**FEATURES**

**Interactive Flashcards**: Learn Turkish with ease by flipping through flashcards showing Turkish words and their English translations.

**Track Your Progress**: Keep tabs on the words you’ve mastered and the ones you’re still working on.

**Set Your Own Pace**: Use customizable timers to automatically flip cards, making practice sessions more efficient.

**Save Your Progress**: Your learning journey is saved locally, so you can pick up right where you left off.

**REQUIREMENTS**
Python 3.x
Tkinter (built-in with Python standard library)
pandas (pip install pandas)

**INSTALLATION**
Ensure you have the required Python version and libraries installed
pip install pandas
pip install tkinter

**HOW TO USE**
Run the application:python main.py
Use the ✓ (Known) button to mark a word as learned.
Use the ✗ (Unknown) button to move to the next word.
The app saves progress in data/words_to_learn.csv.

**CUSTOMIZATION**
To change the dataset, replace "data/turkish.csv" with a new file following the same format.
Adjust the flip timer duration in the main.py file by modifying this line:
"flip_timer = window.after(3000, func=flip_card)  # Time in milliseconds"

**LICENSE**
This project is open-source. Feel free to use and modify it to suit your needs.

