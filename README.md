# QR Code Generator 
### is a web-based tool that allows users to generate QR codes for a list of URLs. It provides a simple interface to input URLs, generate QR codes in real-time, and view them in a responsive layout.

![Screenshot](https://raw.githubusercontent.com/RokasBakunas/python-qr/main/image/python-qr.png)

### Features:
1. Simple URL Input: Users can input multiple URLs (one per line) to generate QR codes.
2. Real-time QR Code Generation: QR codes are generated in real-time as users input URLs.
3. Responsive Display: QR codes are displayed in rows that adapt to the screen size.
4. Download Functionality: Users can download individual QR codes as well as all codes in a consolidated image.

### Dependencies:
Flask: For web server setup.
qrcode: For QR code generation.


### Setup and Usage:
Ensure you have Python and the required libraries installed.

Clone or download this project to your local machine.

### Navigate to the project directory and install the required Python libraries:
```
pip3 install Flask qrcode
```

### Run the application:
```
python3 app.py
```
### Open a web browser and navigate to http://127.0.0.1:8881/.

Input your URLs (one per line) and click "Generate QR Codes" to view the QR codes.
Click on individual QR codes to download or use the "Download All QR Codes" button to get all codes in one image.

