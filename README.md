# 📄 AI Agent - Amazon Invoice Extractor  
This AI-powered automation tool **logs into Amazon**, navigates to order history, **downloads the latest invoices**, extracts order details from the **PDF**, and **saves them to a Google Drive folder**.  

## 🚀 Features  
✅ Automated login to **Amazon Orders Page**  
✅ **Downloads invoice PDFs** and extracts order details  
✅ **Stores invoices in Google Drive** for easy access  
✅ Uses **Selenium** with an **undetected Chrome driver**  
✅ Implements **PyMuPDF (fitz)** for text extraction  

---

## 🛠️ Technologies Used  
- **Python** (Automation & PDF Processing)  
- **Selenium** (Web Scraping & Automation)  
- **Undetected Chromedriver** (Bypass bot detection)  
- **Streamlit** (UI Interface)  
- **PyMuPDF (fitz)** (PDF text extraction)  

---

2️⃣ Install Required Dependencies

pip install -r requirements.txt

3️⃣ Set Up Amazon Credentials

Create an .env file in the project directory and add your Amazon login credentials:

AMAZON_EMAIL=your-email@example.com

AMAZON_PASSWORD=yourpassword

4️⃣ Run the Application

streamlit run app.py

🔧 How It Works

Logs into Amazon (handles authentication automatically).

Navigates to Order History and selects the latest invoice.

Downloads the invoice PDF and saves it to a Google Drive folder.

Extracts text from the invoice using PyMuPDF.

Displays extracted order details in the Streamlit UI.

📂 Folder Structure

📁 amazon-invoice-extractor

 ├── 📜 app.py             # Main script for automation & UI  
 ├── 📜 requirements.txt   # Dependencies  
 ├── 📂 GDrive-Invoices/   # Folder where invoices are saved  
 ├── 📜 .env               # Environment variables (Amazon credentials)  
 ├── 📜 README.md          # Project documentation  

🎯 Example Output

Downloaded Invoice Path: G:/My Drive/Amazon_Invoices/invoice.pdf

Extracted Order Details (Example):

Order ID: #123-4567890-1234567

Item: Wireless Mouse

Price: ₹1,499

Date: February 20, 2025


