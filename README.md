# FILE HANDLING UTILITY

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: DIXANT NEGI

*INTERN ID*: CT08RWI

*DOMAIN*: JAVA

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

This Java program is designed to demonstrate fundamental file operations, including creating, writing, reading, and modifying a text file. It begins by checking whether a file named "MYFIRSTFILE.txt" exists in the directory. If the file is not found, it creates a new one and confirms its creation. If the file already exists, the program simply acknowledges its presence without creating a duplicate.

Once the file is ready, the program writes predefined content into it. Using the FileWriter class, it adds a few lines of text, including a statement about Java and an age reference. The writing process ensures that the content is stored properly before closing the file to avoid data loss.

After writing, the program proceeds to read the file’s contents. It utilizes the Scanner class to fetch and print each line from the file onto the console. Additionally, it retrieves and displays the file’s name and its absolute path, providing useful metadata about the file’s location.

Beyond basic reading, the program also implements a modification feature. It reads the entire file’s content into a StringBuilder, allowing manipulation of the stored text. The program attempts to replace a specific phrase—"i am shivangi sharma hi"—with "java is so cool". However, since the original phrase does not exist in the file, no actual modification takes place. This highlights a potential flaw in the logic, as the replacement is ineffective without ensuring the target text is present.

Finally, the program writes the (potentially modified) content back into the file, preserving any changes made. After completing all operations, it confirms successful modification. Although the replacement attempt does not alter the content in this case, the structure allows for future modifications if the correct text exists.

This program effectively demonstrates file handling in Java, covering creation, writing, reading, and modifying files. However, some improvements could enhance its functionality. For instance, verifying whether the target text exists before attempting replacement would make modifications more meaningful. Additionally, rather than overwriting the file entirely, an append mode could be introduced to retain previous data while adding new content. Proper exception handling is already included, preventing crashes due to file-related errors. Overall, this program serves as a solid introduction to Java’s file-handling capabilities.

OUTPUT

![Image](https://github.com/user-attachments/assets/f8ab36ab-0bdc-438d-9fba-47a4879bb1b6)
