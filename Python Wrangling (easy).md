```markdown
# Python Wrangling (easy)

## Overview
This document provides the steps to complete the "Python Wrangling (easy)" CTF challenge. The challenge involves using a Python script to decrypt an encoded flag file with a provided password.

## Steps to Complete the Challenge

### 1. Download the Challenge Files

1. Use the `wget` command to download the challenge files, which include:
   - A Python script
   - An encoded text file that contains the flag
   - A password file

   ```bash
   wget <URL_of_python_script>
   wget <URL_of_encoded_text_file>
   wget <URL_of_password_file>
   ```

### 2. Inspect the Python Script

1. Use the `cat` command to read the contents of the Python script:

   ```bash
   cat <python_script_name.py>
   ```

2. Observe that the script interacts with a file named `pole.txt` and supports two arguments (`-e` for encoding and `-d` for decoding).

### 3. Prepare the Encoded Flag File

1. Rename the encoded file to `pole.txt` using the `cp` command:

   ```bash
   cp <encoded_flag_file> pole.txt
   ```

### 4. Decrypt the Flag

1. Run the Python script with the `-d` argument to decrypt the `pole.txt` file:

   ```bash
   python3 <python_script_name.py> -d pole.txt
   ```

2. When prompted for a password, use the contents of the `pw.txt` file. Use the terminal hotkeys for copy/paste:
   - Copy: `ctrl+shift+c`
   - Paste: `ctrl+shift+v`

### 5. Retrieve the Flag

1. The output will display the decrypted flag.

**Flag:** `picoCTF{4p0110_1n_7h3_h0us3_67c6cc96}`

## Additional Notes

- Ensure you have all required files and the correct file names.
- Follow the terminal commands carefully to avoid errors.
```

