
# 📦 Project Zipper

**Project Zipper** is a command-line tool that allows users to easily create a ZIP archive of selected files or projects using interactive prompts. It’s a handy utility for developers, students, or anyone who wants to bundle their code, folders, or documents quickly.

---

## 🚀 Features

- 🔍 Interactive prompts for selecting files and folders  
- 🗂️ Automatically creates a `.zip` archive  
- 📝 Custom naming for your ZIP file  
- 🧩 Cross-platform support  
- ✅ Easy to use, minimal setup

---

## 🛠️ Technologies Used

- Node.js (or Python)  
- Inquirer.js / readline-sync (for CLI prompts)  
- `fs` and `archiver` modules (Node.js) or `zipfile` (Python)

---

## 📥 Installation

```bash
git clone https://github.com/your-username/project-zipper.git
cd project-zipper
npm install   # If using Node.js
```

Or, if you're using Python:

```bash
pip install -r requirements.txt
```

---

## 🧑‍💻 Usage

Run the project using:

```bash
node index.js
```

Or for Python:

```bash
python main.py
```

Follow the prompts:
- Choose files/folders to include
- Name your zip file
- The zip will be created in the `/output` directory

---

## 📁 Folder Structure

```
project-zipper/
│
├── index.js / main.py
├── package.json / requirements.txt
├── output/
│   └── your-archive.zip
├── README.md
```

---

## 📝 Example Prompt

```
? Select the files or folders to zip:
  [x] /project1
  [ ] /notes.txt
  [x] /assignment/

? Enter name for the ZIP file:
> final-submission.zip

✔ Zip created
```
