
Snap2Doc
=======

# 📄 Web2PDFly

Web2PDFly is a Django-based web application that allows users to convert web pages into **readable, customizable PDF documents**.
The platform focuses on **simplicity, readability, and convenience**, making it easy to save online content for offline use, printing, or archiving.

---

## 🚀 Features

* 🌐 **Convert Web Pages to PDF** – Paste any URL and generate a clean PDF.
* 👤 **User Authentication** – Sign up, log in, and save your conversions.
* 🎨 **Custom PDF Options** – Adjust layout, font size, margins, and colors.
* 💾 **Save & Retrieve** – Access previously generated PDFs anytime.
* ☁️ **Cloud Integration** – Save directly to Google Drive, Dropbox, or OneDrive (planned).
* 🖨️ **Print-Friendly Mode** – Remove ads, popups, and clutter for a clean output.
* 📊 **Analytics Dashboard** – Track popular conversions and user activity.
* 📱 **Responsive Design** – Works seamlessly on desktop and mobile devices.

---

## 🛠️ Tech Stack

* **Backend:** Django (Python)
* **Frontend:** Django Templates / Bootstrap (can extend to React if needed)
* **Database:** SQLite (default, can switch to PostgreSQL/MySQL)
* **PDF Generation:** WeasyPrint / xhtml2pdf
* **Authentication:** Django Auth System

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/123abhisek/Snap2Doc.git
cd Snap2Doc
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Apply Migrations

```bash
python manage.py migrate
```

### 5️⃣ Run Development Server

```bash
python manage.py runserver
```

Now visit: [http://127.0.0.1:8000/](http://127.0.0.1:8000/) 🎉

---

## 📖 Usage

1. Enter the URL of a web page.
2. Choose your PDF customization options (layout, font, margins).
3. Click **Convert** to generate and download your PDF.
4. (Optional) Log in to save your PDFs and access them later.

---

## 🔮 Roadmap

* ✅ Basic conversion (MVP)
* ✅ User authentication & profile settings
* 🔲 Batch conversion (multiple URLs at once)
* 🔲 Cloud storage integration (Google Drive, Dropbox, OneDrive)
* 🔲 Browser extension for one-click conversion
* 🔲 Premium features (watermark-free, advanced customization)

---

## 🤝 Contributing

Contributions are welcome! Please fork the repo, create a new branch, and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.
>>>>>>> 71e3606 (initial commit)
