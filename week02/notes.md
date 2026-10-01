# Coding Café - Lab 1 Notes

### 1 · Where am I?
* **Q1:** The `pwd` command printed my current home directory absolute path, which is `/home/ubuntu`.
* **Q2:** The `ls -a` command showed hidden files and directories (those starting with a dot, like `.` and `..`), which are ignored by plain `ls`.
* **Q3:** The first column in `ls -l` represents the file type and access permissions (read, write, and execute privileges) for the owner, group, and others.

### 2 · Build the folder
* **Q4:** It works because `coding-cafe/week02` is a relative path. It points to the directory starting from my current location (the home folder) rather than starting from the root directory.

### 3 · Move, copy, rename, delete
* **Q5:** The `mv` command performed two different actions: first, it moved a file into a subdirectory (`week01/`), and second, it renamed a file (`README-backup.md` to `old-readme.md`).

### 4 · Where does the shell find things?
* **Q6:** There are around 20 to 30 folders on my PATH variable because WSL appends my Windows environment directories to my Linux directory list.
* **Q7:** My python3 binary lives exactly at `/usr/bin/python3`.
* **Q8:** They are not necessarily the same because different operating systems, package managers, or local configurations install Python to different directories.
* **Q9:** The shell printed `command not found: pyton3`. This means the shell searched sequentially through every folder listed in my PATH environment variable and could not find an executable file matching that misspelled name.

### 5 · A box of your own
* **Q10:** The `.venv` folder starts with a leading dot, which flags it as a hidden directory that plain `ls` intentionally skips.
* **Q11:** My terminal prompt changed to show `(.venv)` at the very beginning of the line, indicating that the virtual environment is currently active.
* **Q12:** No, it is not the same path; it now points inside `/home/ubuntu/coding-cafe/.venv/bin/python3`. This tells me that the activate script prepended the virtual environment's local bin folder to the front of my PATH variable.
* **Q13:** The second list contains the `requests` package along with its dependencies (such as `charset-normalizer`, `idna`, `urllib3`, and `certifi`) which were absent in the first list.
* **Q14:** The `python3` command points back to the original global system Python path at `/usr/bin/python3`.

### 6 · Read a manual
* **Q15:** The `ls -h` flag stands for human-readable. It formats file sizes using easy-to-read units like Kilobytes (K), Megabytes (M), or Gigabytes (G) instead of displaying raw byte counts.

### 7 · Work faster
* **Q16:** `Ctrl + C` sends an interrupt signal (SIGINT) to stop or clear the current running line entry. `Ctrl + D` sends an End-of-File (EOF) signal, which closes the active program or logs out of the session entirely.
