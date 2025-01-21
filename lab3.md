1. Define the lab_file shell variable:
First, set the shell variable lab_file to the path of the file editing_final_lab.txt.
lab_file="editing_final_lab.txt"

2. Edit the file using vim:
To open the file in vim (a text editor), use the following command:
vim $lab_file

3. Enter Visual Mode in vim:
To enter visual mode in vim, press v (lowercase) in normal mode. This will allow you to select text.

4. Remove the last seven characters from the first column of the first line:
Place the cursor at the beginning of the line (if you're not already there).
In visual mode, use the arrow keys to highlight the characters you want to remove (in this case, the last 7 characters of the first column).
Once the 7 characters are highlighted, press x to delete them.

5. Preserve only the first four characters of the first column:
If you want to ensure that only the first four characters of the first column remain, after deleting the last seven characters, ensure the cursor is at the fourth character of the first column (or use the arrow keys).

6. Save and Exit:
After editing the file, save your changes and exit vim using:
:wq

7. Edit the file using nano:
If you'd like to edit the same file using nano instead of vim, you can open it with:
nano $lab_file




<img width="560" alt="Screenshot 2025-01-21 at 12 30 51 PM" src="https://github.com/user-attachments/assets/710d6012-b074-4cbb-9b5e-5363bc5b0b16" />
