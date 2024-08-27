## **PW Crack 5 (Medium)**

## 📝 Challenge Overview
In this challenge, your task is to crack a password by matching a hash value with a password from a dictionary file.

## 🚀 Steps to Solve

1. Download the Challenge Files
   Use `wget` to download the necessary files to your virtual machine:
   ```bash
   wget <URL-to-challenge-files>

2. Examine the Python Script
Use cat or nano to inspect the Python script and understand its logic:

bash
Copy code
cat level5.py
Identify the part of the script where the hash is verified against the dictionary.
3. Match the Hash
Compare the hash found in the script with the entries in dictionary.txt to identify the correct password.

4. Run the Python Script
After finding the correct password, execute the script:

bash
Copy code
python3 level5.py
Enter the correct password when prompted.
5. Retrieve the Flag
After successfully entering the correct password, the script will reveal the flag.

🏁 Flag
FLAG: picoCTF{h45h_sl1ng1ng_fffcda23}
