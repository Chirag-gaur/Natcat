# Natcat
Browser


# Step-by-Step Guide to Run Browser

## Step 1: Open Drive Link
- Navigate to the provided drive link.

## Step 2: Download File
- Download the `browser.html.enc` file.

## Step 3: Open Terminal
- Launch your terminal application.

## Step 4: Run the Following Commands
1. Change to the Downloads directory:
   ```bash
   cd Download/
   nc -l 8080 < browser.html.enc 
   openssl enc -aes-256-cbc -d -in browser.html.enc -out message.html -k redhat
   xdg-open message.html
   ```
