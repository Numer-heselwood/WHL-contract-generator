# 📝 Contract Generator Web App

This is a Streamlit web application that allows users to upload multiple Word `.docx` contract templates containing placeholders like `{{Date}}`, `{{contract_name}}`, etc., fill in shared values, and generate filled documents — all in your browser!

## 🚀 Features

- Upload multiple `.docx` templates
- Fill in shared fields like date, contract name, invoice number, etc.
- Automatically replace placeholders in the uploaded documents
- Download all generated documents as a single `.zip` file
- Preserves original font and formatting

---

## 📦 Demo

Try it live: [https://your-app.streamlit.app](https://your-app.streamlit.app)  
*(Replace with your actual deployed link)*

---

## 🧩 Template Format

Use Word templates with placeholders in double curly braces, like:

```text
Contract No: {{contract_name}}

Date: {{Date}}

Invoice No: {{invoice_no}}

Total Amount: {{amount}}
