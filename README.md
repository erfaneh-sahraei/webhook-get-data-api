# Google Sheets GET API Webhook

A professional n8n automation project that turns your Google Sheet into a dynamic REST API. It triggers via an HTTP `GET` request, fetches data from a Google Sheet, and returns it instantly to the client as a structured JSON response.

---

## 🚀 How It Works

1. **Trigger:** A client (such as Postman, a web browser, or another app) sends an HTTP `GET` request to your n8n Webhook URL.
2. **Data Retrieval:** The workflow queries your connected Google Sheet to pull the required records.
3. **JSON Response:** n8n processes the sheet data and responds back to the client with a clean JSON payload.

---

## 📂 Project Structure
```text
├── Google Sheets GET API Webhook.json  # n8n workflow export file
├── sample-response.json                # Example JSON data returned by the API
└── README.md                           # Project documentation
