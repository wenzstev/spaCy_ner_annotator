# spaCy NER Annotator

The spaCy NER Annotator is a script to make it easier to annotate training examples for spaCy's Named Entity Recognizer.

## Usage

The annotator accepts files in .txt or .py. You can try other formats, but success may vary.
To initialize, use the command -tf to designate the training file, and the command -e to designate the entity.
If you do not use any commands when initalizing, the script will ask you for the training file and entity when it starts.

The annotator will then loop through all lines in the provided annotator file. For each line, it will prompt you to type in
the entity, or entities on the line. More than one example can be entered with the use of a comma (',').

You can annotate only one entity type at a time, but it is easy to repeat the process multiple times on the same lines of data.

After completing all lines, the program will prompt you for a name and save the file as .py. The data will be properly formatted;
you may use it immediately or run the program again to annotate for another entity.

