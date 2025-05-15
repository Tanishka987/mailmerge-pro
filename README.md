# 📧 MailMerge Pro

**MailMerge Pro** is a web-based tool to send personalized emails to multiple recipients using Gmail and data from a Google Sheet or CSV file.

🔗 **Live Site**: [https://tanishka987.github.io/mailmerge-pro/](https://tanishka987.github.io/mailmerge-pro/)

---

## 🚀 How to Use

### 1️⃣ Authorize with Google

- Click the **"Authorize"** button.
- Grant permission to:
  - Read your Google Sheets
  - Send emails via Gmail

> ✅ Make sure you are logged into the correct Google account.

---

### 2️⃣ Load Recipients

You have **two options**:

#### Option A: Google Sheet
- Paste your **Google Spreadsheet ID** into the input box.
- Click **"Load Recipients"** to fetch names and email addresses.

> 📌 Your sheet must have at least these columns:  
`name`, `email`

#### Option B: Upload CSV
- Click the **"Upload CSV"** button.
- Select a file with `name` and `email` columns.

---

### 3️⃣ Compose Email

- Add a **Subject**.
- Use the **message editor** to write your email:
  - Format text (bold, italic, underline)
  - Add bullet lists
  - Insert **images**
  - Use **HTML elements**
- Use recipient variables like:
  - `{{name}}` → replaced with the recipient's name

---

### 4️⃣ Send a Test Email

- Before sending to all, click **"Send Test Email"**.
- The test email will be sent to **your authorized Gmail** address.
- Review how it looks in your inbox.

---

### 5️⃣ Send to All Recipients

- Once you’re satisfied, click **"Send Emails"**.
- The app will send personalized emails to each recipient.
- A progress bar will show the status live.

---

## 🛡️ Privacy & Security

- This tool uses Google OAuth 2.0 — **your credentials are not stored**.
- Email sending happens **through your Gmail account** directly via Google's APIs.

---

## ✅ Features

- Google Sign-In with secure OAuth
- CSV or Google Sheet support
- HTML Email Editor with:
  - Rich text formatting
  - Image support
- Dynamic placeholders like `{{name}}`
- Test mode
- Progress tracker

---

## 🔗 Technologies

- JavaScript
- Google APIs (Gmail, Sheets)
- Google Identity Services
- HTML, CSS

---

## 📄 License

MIT License © 2025 [Tanishka987](https://github.com/Tanishka987)
