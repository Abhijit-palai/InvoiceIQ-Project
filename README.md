 InvoiceIQ: AI-Powered Invoice Extractor

InvoiceIQ is a Streamlit-based application powered by Google Gemini Vision (1.5 Flash) that extracts and interprets information from invoices.
You can upload invoice images and ask natural-language questions like:

"What’s the invoice number?"

"Who is the vendor?"

"What is the total amount due?"

 Features

Upload invoices in JPG, JPEG, or PNG format

Ask custom questions about the uploaded invoice

Uses Gemini Vision (Google Generative AI) for intelligent extraction

Displays AI-generated responses in a clean Streamlit UI

Simple, lightweight, and easily extensible

 Tech Stack

Python 3.10+

Streamlit – Web UI

Google Generative AI (Gemini 1.5 Flash) – Multimodal invoice analysis

PIL (Pillow) – Image handling

dotenv – Environment variable management

 Installation & Setup


cd invoiceiq


Create and activate a virtual environment

python -m venv geminienv

geminienv\Scripts\activate      


Install dependencies

pip install -r requirements.txt


Set up environment variables

Create a .env file in the project root

Add  Google API key:

GOOGLE_API_KEY="AIzaSyCWKB1CD6U9Z1udjlSYxsUpZgbIsAawMOY"


Run the app

streamlit run app.py


 Project Structure

InvoiceIQ/
│── app.py              # Main Streamlit app
│── requirements.txt    # Dependencies
│── .env                # Example environment variables
│── README.md           # Documentation

Future Improvements

Extract structured fields (Invoice No, Date, Vendor, Total) into a table

Export extracted data to CSV/Excel

Support for PDF invoices

Multi-language invoice support

 Contributing

Contributions are welcome! Feel free to fork this repo, create a feature branch, and submit a pull request.

 License

This project is licensed under the MIT License.

 Built with  using Google Gemini & Streamlit
