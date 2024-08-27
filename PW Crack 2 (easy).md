PW Crack 2 (Easy)

📝 Challenge Overview
In this challenge, your task is to crack a password by analyzing a Python script to find the embedded password.

🚀 Steps to Solve

Download the Challenge Files
Use wget to download the necessary files to your virtual machine:
wget <URL-to-challenge-files>

Examine the Python Script
Use cat or nano to inspect the Python script and locate the line where the password is assigned:
cat level2.py
Look for a line similar to user_pw = "password".

Run the Python Script
After identifying the password, execute the script:
python3 level2.py
Enter the password when prompted.

Retrieve the Flag
After successfully entering the correct password, the script will reveal the flag.

🏁 Flag
FLAG: picoCTF{tr45h_51ng1ng_9701e681}
