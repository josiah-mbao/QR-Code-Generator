# QR Code Generator with Email Integration

This project allows users to generate QR codes that encode ticket information, which is then sent to a specified email address. The backend is built using Python with Flask, and it utilizes Gmail for email sending. The frontend allows users to input their email and ticket information to generate the QR code and view it directly in the browser.

## Live demo
<img width="1431" alt="Screenshot 2025-04-10 at 11 46 23" src="https://github.com/user-attachments/assets/c0575b4d-652f-462e-93b1-afa423000190" />
<img width="1440" alt="Screenshot 2025-04-10 at 11 38 58" src="https://github.com/user-attachments/assets/aa9ea43b-c784-4a01-a0c3-8f64771d7a97" />



## Features

- Users can enter text (such as ticket information) and email address.
- A QR code is generated based on the input data.
- The QR code is displayed on the frontend.
- The QR code is also sent to the provided email address.
- Built with Flask, Python, and Gmail for email integration.
- Deployable on Google Cloud Platform (GCP).

## Getting Started

### Prerequisites

Make sure you have Python and pip installed on your machine.

- Python 3.x
- pip (Python package installer)

You will also need a Gmail account for sending emails. Set up your Gmail SMTP credentials using the `dotenv` package to load the environment variables securely.

### Installing

1. Clone the repository:

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

2. Create a virtual environment (recommended):

```bash
git clone https://github.com/yourusername/qr-code-generator.git
cd qr-code-generator

3. Install the required packages:

```bash
pip install -r requirements.txt

4. Set up your environment variables in a .env file (in the root directory of the project):

```bash
GMAIL_USER=your-email@gmail.com
GMAIL_PASSWORD=your-app-password

Make sure to use App Passwords for security.

5. Run the application locally:

```bash
python app.py

This will start the Flask server on http://127.0.0.1:5000/.
