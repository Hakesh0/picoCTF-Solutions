```markdown
# Scan Surprise (easy)

## Overview
This document outlines the steps to complete the "Scan Surprise (easy)" CTF challenge. The challenge involves using `wget` to download a file, extracting its contents, and scanning an image for a hidden flag.

## Steps to Complete the Challenge

### 1. Download the File

Use `wget` to download the file to your virtual machine. Replace `<URL>` with the actual URL of the file:

```bash
wget <URL>
```

### 2. Extract the File

Once the file is downloaded, extract its contents. The file is typically in a compressed format, so you can use the following command:

```bash
tar -xvf <file-name>
```

Replace `<file-name>` with the name of the downloaded file.

### 3. Scan the Image

Navigate to the directory where the extracted files are located. Locate the image file and use a tool to scan it for hidden information. You might use `binwalk`, `steghide`, or any other steganography tool depending on the type of hidden data.

For example, if you are using `binwalk`:

```bash
binwalk <image-file>
```

Or if you are using `steghide`:

```bash
steghide extract -sf <image-file>
```

Replace `<image-file>` with the name of the image file you found.

### 4. Retrieve the Flag

After scanning the image, you should find a hidden flag. In this challenge, the flag is:

**Flag:** `picoCTF{p33k_@_b00_19eccd10}`

## Additional Notes

- Ensure you have the necessary tools installed for file extraction and image scanning.
- The file and its contents are meant to be handled in a secure environment.
```
