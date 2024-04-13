<h1>Updating the Written Sentence</h1>


<h2>Description</h2>
The 'Sentence' class in this project represents a sentence and provides methods to manipulate and retrieve information about the sentence. The class has the following methods:

'__init__(self, sentence)': The constructor method initializes a 'Sentence' object with the provided sentence.

'get_first_word(self)': This method returns the first word of the sentence. It splits the sentence into words using the 'split()' method, checks if there are any words in the sentence, and returns the first word if it exists. If there are no words, it returns None.

'get_all_words(self)': This method returns a list of all the words in the sentence. It splits the sentence into words using the 'split()' method and returns the resulting list.

'replace(self, index, new_word)': This method allows for updating the sentence by replacing a word at a specified index. It splits the sentence into words, checks if the provided index is within the valid range of indices, replaces the word at the specified index with the new word, and updates the sentence by joining the modified words with spaces.

'__str__(self)': This method overrides the 'str()' function to provide a string representation of the 'Sentence' object. It returns the current sentence.

The program prompts the user to enter a sentence and creates a 'Sentence' object using the input. It then demonstrates the functionality of the class by printing the first word of the sentence, all the words in the sentence, and prompting the user to enter an index and a new word to update the sentence. After the replacement, it displays the updated sentence.

This project showcases how to manipulate sentences by extracting words, replacing words at specific indices, and representing the modified sentence as a string. It provides a basic framework that can be expanded upon for more advanced text processing tasks and applications.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 

<h2>Environments Used </h2>

- <b>Jupyter Notebook</b> 

