# Input, Output and Files

## Skill Description:

A fellow is able to manipulate files and folders within an application and implement Hashing.

# Output:

**Task:** Create a file system that includes, creating files, folders, moving files from one folder to another within a 
main folder. Use the “Hash” of a file to check if a file has been updated or changed.

### Knowledge: 
| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| What is I/O? | [ ] | [ ] |
| What is a file? | [ ] | [ ] |
| How to print to the screen. | [ ] | [ ] |
| How to open and close files. | [ ] | [ ] |
| How to read and write to files. | [ ] | [ ] |
| How to obtain the position of a file | [ ] | [ ] |
| How to rename and delete files. | [ ] | [ ] |
| How to create, rename and change directories. | [ ] | [ ] |
| The attributes and modes of a file | [ ] | [ ] |
| What is Hashing? | [ ] | [ ] |


### Behaviours:
| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When I want to get a file object, **Action:** I use Python’s built in open function | [ ] | [ ] | 
| **Context:** For the correct and efficient computation of the hash value of a file, **Action:** Open the file in binary mode to avoid character encoding, Don't read the complete file into memory, since that is a waste of memory. Instead, sequentially read it block by block and update the hash for each block.Eliminate double buffering, i.e. don't use buffered IO, because we already use an optimal block size.| [ ] | [ ] |


### Beliefs:
| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| When you’re working with Python, you don’t need to import a library in order to read and write files. It’s handled natively in the language, albeit in a unique manner. | [ ] | [ ] |
| In Python, a file is categorized as either text or binary, and the difference between the two file types is important. | [ ] | [ ] |


### Resources:

- [Python - Files/IO](https://www.tutorialspoint.com/python/python_files_io.htm)
- [Python Input and Output](https://www.javatpoint.com/python-files-io)
- [Reading and Writing Files in Python](https://www.pythonforbeginners.com/files/reading-and-writing-files-in-python)
- [Monitoring if a File has changed in Python](https://mygisblog.wordpress.com/2014/08/03/monitoring-if-a-file-has-changed-in-python/)
