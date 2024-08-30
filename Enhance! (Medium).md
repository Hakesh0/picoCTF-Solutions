```markdown
# Enhance! (Medium)

## 📝 Challenge Overview
In this challenge, your task is to extract hidden information from an image file to retrieve the flag.

## 🚀 Steps to Solve

1. **Download the Image File**  
   Use `wget` to download the image file to your virtual machine:  
   ```bash
   wget <URL-to-challenge-files>
   ```

2. **Examine the Image File**  
   Use `cat` or `strings` to examine the content of the image file:  
   ```bash
   cat drawing.flag.svg
   ```
   or
   ```bash
   strings drawing.flag.svg
   ```

3. **Extract the Flag**  
   The content of the file may be separated by `<tspan>` tags. Use the following command to filter out the lines that contain the flag:  
   ```bash
   strings drawing.flag.svg | grep "</tspan>"
   ```

4. **Retrieve the Flag**  
   The output from the above command will reveal the flag.

## 🏁 Flag
**FLAG:** ` picoCTF{3nh4nc3d_d0a757bf}`
```

