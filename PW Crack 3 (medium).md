```markdown
# PW Crack 3 (medium)

## Challenge Description
In this challenge, you are required to decrypt a hash and find the correct password among several options to obtain the flag.

## Steps to Solve

1. **Download the Files**
   - Use `wget` to download the necessary files to your virtual machine:
     ```bash
     wget <URL_of_the_files>
     ```

2. **Decrypt the Hash**
   - Analyze the provided files to decrypt the hash and find the correct password. This may require using online tools or scripts to crack the hash.

3. **Inspect the Python Script**
   - Open the Python script using `cat` or `nano` to examine its contents:
     ```bash
     cat level3.py
     ```
   - The script contains seven possible passwords, but only one matches the decrypted hash. Look for the line that sets the user password:
     ```python
     user_pw = "<password>"
     ```

4. **Verify the Correct Password**
   - Compare the decrypted hash with the possible passwords in the script to determine the correct one.

5. **Run the Python Script**
   - Execute the script using `python3` and provide the correct password when prompted:
     ```bash
     python3 level3.py
     ```
   - Enter the verified password to retrieve the flag.

## Flag
```plaintext
picoCTF{m45h_fl1ng1ng_6f98a49f}
```

## Summary
By decrypting the hash and identifying the correct password in the script, you can run the script successfully and obtain the flag.
```
