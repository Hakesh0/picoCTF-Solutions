```markdown
# **PW Crack 1 (Easy)**

## 📝 Challenge Overview
In this challenge, you'll need to crack a password by analyzing a Python script and extracting the hardcoded password.

## 🚀 Steps to Solve

### 1. **Download the Challenge Files**
   Use `wget` to download the necessary files to your virtual machine:
   ```bash
   wget <URL-to-challenge-files>
   ```

### 2. **Examine the Python Script**
   Use `cat` or `nano` to inspect the Python script and understand its logic:
   ```bash
   cat level1.py
   ```
   - Search for the line where the `user_pw` variable is defined.

### 3. **Run the Python Script**
   After identifying the password, execute the script:
   ```bash
   python3 level1.py
   ```
   - Enter the extracted password when prompted.

### 4. **Retrieve the Flag**
   After successfully entering the correct password, the script will output the flag.

## 🏁 Flag
**FLAG:** `picoCTF{545h_r1ng1ng_1b2fd683}`
```
