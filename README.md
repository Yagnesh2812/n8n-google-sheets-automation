# 🚀 n8n Google Sheets Data Enrichment Automation

This project demonstrates an automated workflow built using **n8n** that reads customer data from Google Sheets, enriches it using multiple APIs, updates the sheet, and sends an automated email.

---

## 📌 Features

* 📥 Fetch customer data from Google Sheets
* 🌐 Enrich data using APIs:

  * Gender prediction (Genderize API)
  * Age prediction (Agify API)
  * Nationality prediction (Nationalize API)
* 📊 Update enriched data back into Google Sheets
* 📧 Send automated email notifications

---

## ⚙️ Workflow Overview

1. **Manual Trigger** – Start workflow execution
2. **Get Data** – Fetch rows from Google Sheets
3. **API Processing**:

   * Gender Detection
   * Age Prediction
   * Country Prediction
4. **Update Data** – Store enriched data in Google Sheets
5. **Send Email** – Notify the user via Gmail

---

## 🧩 Technologies Used

* n8n (Workflow Automation Tool)
* Google Sheets API
* Gmail API
* REST APIs:

  * https://api.genderize.io/
  * https://api.agify.io/
  * https://api.nationalize.io/

---

## 📂 Data Structure

| Id | Name | Number | Gender | Age | Country |
| -- | ---- | ------ | ------ | --- | ------- |

---

## 🔧 Setup Instructions

1. Install n8n globally:

   ```bash
   npm install n8n -g
   ```

2. Start n8n:

   ```bash
   n8n
   ```

3. Import the provided workflow JSON file

4. Configure credentials:

   * Google Sheets OAuth2
   * Gmail OAuth2

5. Prepare your Google Sheet with:

   * Id, Name, Number

6. Execute the workflow

---

## 📸 Use Case

* Customer Data Enrichment
* CRM Automation
* Lead Management
* Marketing Automation

---

## 🚧 Future Improvements

* Add error handling
* Add webhook trigger (real-time automation)
* Improve data validation
* Add logging & monitoring

---

## 👨‍💻 Author

Yagnesh Gadhethariya
