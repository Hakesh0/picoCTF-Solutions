```markdown
# PW Crack 2 (easy)

## Challenge Description
In this challenge, you are required to crack another password-protected Python script to obtain the flag.

## Steps to Solve

1. **Download the Files**
   - Use `wget` to download the necessary files to your virtual machine:
     ```bash
     wget <URL_of_the_files>
     ```

2. **Inspect the Python Script**
   - Open the Python script using `cat` or `nano` to examine its contents:
     ```bash
     cat level2.py
     ```
   - Look for the line that sets the user password:
     ```python
     user_pw = "<password>"
     ```

3. **Run the Python Script**
   - Execute the script using `python3` and provide the password when prompted:
     ```bash
     python3 level2.py
     ```
   - Enter the password found in the script.

4. **Obtain the Flag**
   - After entering the correct password, the script will reveal the flag.

## Flag
```plaintext
picoCTF{tr45h_51ng1ng_9701e681}
```

## Summary
By inspecting the Python script for the embedded password, you can run the script successfully and retrieve the flag.
```
