```markdown
# PW Crack 4 (medium)

## Challenge Overview
This challenge involves cracking a password by decrypting a hash and finding the correct password from a list of 100 possible options.

## Steps to Solve

1. **Download the Files**
   - Use `wget` to download the challenge files to your virtual machine:
     ```bash
     wget <URL-to-challenge-files>
     ```

2. **Decrypt the Hash**
   - You'll need to decrypt the hash provided in the challenge to find the correct password.

3. **Read the Python Script**
   - Use `cat` or `nano` to read the Python script and understand its logic:
     ```bash
     cat level4.py
     ```
   - Look for the line in the script where the `user_pw` variable is assigned.

4. **Identify the Correct Password**
   - The script includes 100 possible passwords. Only one of them is correct.
   - Verify each password against the hash to find the correct one.

5. **Run the Python Script**
   - Once you've identified the correct password, run the script in the terminal using:
     ```bash
     python3 level4.py
     ```
   - Enter the correct password when prompted.

6. **Obtain the Flag**
   - After entering the correct password, you will receive the flag.

## Flag
**FLAG:** `picoCTF{fl45h_5pr1ng1ng_cf341ff1}`
```
