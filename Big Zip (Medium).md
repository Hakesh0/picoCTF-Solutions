```markdown
# Big Zip (Medium)

## 📝 Challenge Overview
In this challenge, your task is to search through a large number of files in a zip archive to find the hidden flag.

## 🚀 Steps to Solve

1. **Download the Zip File**  
   Use `wget` to download the zip file to your virtual machine:  
   ```bash
   wget <URL-to-challenge-files>
   ```
   ```

2. **Extract the Zip File**  
   Use the `unzip` command to extract the contents of the zip file:  
   ```bash
   unzip <zip-file-name>
   ```

3. **Search for the Flag**  
   After extracting the contents, use the `grep` command to search through all files and subdirectories for the flag. The `-r` flag will search recursively :
   ```bash
   grep -r "picoCTF"
   ```

4. **Retrieve the Flag**  
   The output of the `grep` command will reveal the flag.

## 🏁 Flag
**FLAG:** picoCTF{gr3p_15_m4g1c_ef8790dc}
```
