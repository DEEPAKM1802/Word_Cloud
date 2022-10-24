For this project, we will create a "word cloud" from a text by writing a script. This script needs to process the text, remove punctuation, ignore case and words that do not contain all alphabets, count the frequencies, and ignore uninteresting or irrelevant words. A dictionary is the output of the calculate_frequencies function. The wordcloud module will then generate the image from dictionary.

In [1]: For the input text of your script, we will need to provide a file that contains text only.To do the upload, we will need an uploader widget. The first cell performs all the installs and imports for our word cloud script and uploader widget.

IMPORTANT! If this is the first time running the above cell containing the installs and imports, we will need to save this notebook now. Then under the File menu above, select Close and Halt. When the notebook has completely shut down, reopen it. This is the only way the necessary changes will take affect.

In [2]: To upload the text file, run the following cell that contains all the code for a custom uploader widget. Once we run this cell, a "Browse" button should appear below it. Click this button and navigate the window to locate your saved text file. The uploader widget saved the contents of our uploaded file into a string object named file_contents that our word cloud script can process.

In [3]: Tthe cell below iterates through the words in file_contents, removes punctuation, and counts the frequency of each word. It ignores word case, words that do not contain all alphabets and boring words like "and" or "the". Then use it in the generate_from_frequencies function to generate our very own word cloud!

In [4]: Our word cloud image should appear after running this cell. Fingers crossed!