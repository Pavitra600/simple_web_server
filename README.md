# EX01 Developing a Simple Webserver

# Date: 11/11/2024
# AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

# DESIGN STEPS:
## Step 1:
HTML content creation.

## Step 2:
Design of webserver workflow.

## Step 3:
Implementation using Python code.

## Step 4:
Serving the HTML pages.

## Step 5:
Testing the webserver.

# PROGRAM:
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Device Specifications</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <div class="spec-container">
            <h1 class="title">Device Specifications</h1>
            <div class="spec-item">
                <span class="spec-label">Device Name:</span>
                <span class="spec-value">LAPTOP-OK438C1K</span>
            </div>
            <div class="spec-item">
                <span class="spec-label">Processor:</span>
                <span class="spec-value">12th Gen Intel(R) Core(TM) i3-1215U 1.20 GHz</span>
            </div>
            <div class="spec-item">
                <span class="spec-label">Installed RAM:</span>
                <span class="spec-value">8.00 GB (7.68 GB usable)</span>
            </div>
            <div class="spec-item">
                <span class="spec-label">Device ID:</span>
                <span class="spec-value">FED1B711-7C21-464A-9BAA-30A98F1765ED</span>
            </div>
            <div class="spec-item">
                <span class="spec-label">Product ID:</span>
                <span class="spec-value">00356-24754-57891-AAOEM</span>
            </div>
            <div class="spec-item">
                <span class="spec-label">System Type:</span>
                <span class="spec-value">64-bit operating system, x64-based processor</span>
            </div>
            <div class="spec-item">
                <span class="spec-label">Pen and Touch:</span>
                <span class="spec-value">No pen or touch input is available for this display</span>
            </div>
        </div>
    </body>
    </html>

/* styles.css */
    body {
        font-family: 'Arial', sans-serif;
        margin: 0;
        padding: 0;
        background: linear-gradient(to right, #ff9a9e, #fad0c4, #fbc2eb);
        color: #333;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }
    
    .spec-container {
        background-color: #fff;
        border-radius: 12px;
        box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
        padding: 20px;
        width: 80%;
        max-width: 600px;
        text-align: left;
        border: 3px solid #f78fb3;
    }
    
    .title {
        font-size: 26px;
        font-weight: bold;
        text-align: center;
        margin-bottom: 20px;
        color: #ff6b81;
        text-shadow: 1px 1px 3px rgba(255, 105, 135, 0.6);
    }
    
    .spec-item {
        display: flex;
        justify-content: space-between;
        padding: 10px 0;
        border-bottom: 1px solid #f3a6b8;
    }
    
    .spec-label {
        font-weight: bold;
        color: #ff6f91;
    }
    
    .spec-value {
        color: #333;
        font-style: italic;
    }
    
    .spec-item:last-child {
        border-bottom: none;
    }
    
    .spec-container:hover {
        transform: scale(1.03);
        transition: transform 0.3s ease-in-out;
        box-shadow: 0 12px 30px rgba(255, 99, 128, 0.3);
    }

# OUTPUT:
![alt text](<Screenshot 2024-11-25 140940.png>)
![Screenshot 2024-12-12 203357](https://github.com/user-attachments/assets/829fe6b6-3e6c-4d2b-9c75-53202954d0ba)
![image](https://github.com/user-attachments/assets/0f006599-a309-44fa-a246-1cba5b460fcd)

# RESULT:
The program for implementing simple webserver is executed successfully.
