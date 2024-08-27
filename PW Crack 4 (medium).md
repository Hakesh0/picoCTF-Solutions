```markdown
# **PW Crack 4 (Medium)**

## 📝 Challenge Overview
In this challenge, you'll need to crack a password by decrypting a hash and identifying the correct password from a list of 100 possibilities.

## 🚀 Steps to Solve

### 1. **Download the Challenge Files**
   Use `wget` to download the necessary files to your virtual machine:
   ```bash
   wget <URL-to-challenge-files>
   ```

### 2. **Decrypt the Hash**
   Analyze the provided hash to determine the correct password.

### 3. **Examine the Python Script**
   Use `cat` or `nano` to inspect the Python script and understand its logic:
   ```bash
   cat level4.py
   ```
   - Search for the line where the `user_pw` variable is defined.
   - Note the list of 100 possible passwords included in the script.

### 4. **Identify the Correct Password**
   - The script contains 100 passwords, but only one is correct.
   - Verify each password against the hash until you find the correct one.

### 5. **Run the Python Script**
   Once you've identified the correct password, execute the script:
   ```bash
   python3 level4.py
   ```
   - Enter the correct password when prompted.

### 6. **Retrieve the Flag**
   After successfully entering the correct password, the script will output the flag.

## 🏁 Flag
**FLAG:** `picoCTF{fl45h_5pr1ng1ng_cf341ff1}`
```
