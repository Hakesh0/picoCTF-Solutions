Here’s the markdown file for the "IntroToBurp (easy)" CTF challenge:

```markdown
# IntroToBurp (easy)

## Overview
This document provides the steps to complete the "IntroToBurp (easy)" CTF challenge. The challenge involves intercepting and manipulating HTTP requests using Burp Suite to bypass a 2FA authentication page and obtain a flag.

## Steps to Complete the Challenge

### 1. Input Data and Capture with Burp Suite

1. Navigate to the form where you need to input data.
2. Enter some information into the form fields.
3. Click the "Register" button to submit the form.
4. Use Burp Suite to intercept the request:
   - Ensure Burp Suite is set up to intercept traffic from your browser.
   - In Burp Suite, go to the "Proxy" tab and ensure "Intercept is on."

### 2. Forward Request and Access 2FA Page

1. Continue to click the "Forward" button in Burp Suite to move through the intercepted requests.
2. You will reach the 2FA authentication page.

### 3. Manipulate and Forward the Request

1. On the 2FA page, input any value in the 2FA field.
2. In Burp Suite, locate the intercepted request for the 2FA page.
3. Examine the raw request and look for the parameter `otp=123`.
4. Delete the line containing `otp=123` from the request.
5. Click "Forward" in Burp Suite to send the modified request.

### 4. Retrieve the Flag

1. After forwarding the modified request, you will receive a response containing the flag.

**Flag:** `picoCTF{#0TP_Bypvss_SuCc3$S_2e80f1fd}`

## Additional Notes

- Ensure Burp Suite is correctly configured to intercept and modify requests.
- The flag is obtained by bypassing the 2FA authentication through request manipulation.
```
