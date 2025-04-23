# 🎯 Coursera JSON / jQuery / JavaScript Course Helper

Yo! 👋  
This is your one-stop repo to get through the **Coursera JSON / jQuery / JavaScript** course without breaking your brain.  
Just follow the steps below — even if you're running on 2 brain cells and a dream, you’ll be fine 😎

---

## 📦 Repo URL

Clone this bad boy first:

```bash
git clone https://github.com/Suja16/json-jquery-and-javascript.git
```

---

## ✅ What You’ll Need

- 🖥️ XAMPP (for Apache + MySQL)
- 🌐 Ngrok (for submitting live URLs)
- 🧠 Mild awareness of copy-pasting

---

## 🛠️ Setup Instructions

### 1. 📂 Move the Folder to htdocs

After cloning:

- Copy the **entire folder** (`json-jquery-and-javascript`) into:
  ```
  C:\xampp\htdocs\
  ```

> **DON’T** just dump the files inside `htdocs` directly. Keep the folder structure.  

---

### 2. ✏️ Change the `<title>`

Open the file where the `<title>` is (probably `index.php` or similar).  
You’ll see something like this:

```html
<title>6e2de61f</title>
```

- Replace `6e2de61f` with your **Coursera ID** (you’ll find it in the assignment instructions on Coursera).
  
💡 *If you don't change this, Coursera will think you’re cheating.*

---

### 3. ▶️ Start XAMPP Services

- Launch **XAMPP Control Panel**
- Click **Start** for:
  - Apache ✅
  - MySQL ✅

---

### 4. 🧾 Run the SQL Setup

- Go to `http://localhost/phpmyadmin`
- Create a new database (name it whatever you want, e.g., `coursera`)
- Open `setup.txt` from this repo
- Paste the SQL code into the **SQL** tab and run it

---

### 5. 🌐 Use Ngrok to Go Live

Open a terminal and run:

```bash
ngrok http 80
```

- You’ll get a URL like: `https://randomstuff.ngrok.io`
- Test the link in a browser
- **Copy-paste that link into Coursera** as your submission

---

## 🧠 Common Mistakes to Avoid

- ❌ Don’t put the PHP files directly into `htdocs` — use the folder
- ❌ Don’t forget to change the `<title>`
- ❌ Don’t forget to start **both** Apache and MySQL
- ❌ Don’t touch anything you don’t understand

---

## 🥳 That’s It!

Submit your Ngrok link, get your score, and move on with your life like a legend.

---

## 📬 Need Help?

If it breaks or you're stuck, open an issue here or just yell at the nearest coder 😅
