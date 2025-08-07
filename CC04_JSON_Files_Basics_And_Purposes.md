# 🧱 JSON Files: The Basics and Their Purpose

## 📂 What is a JSON file?

**JSON** stands for **JavaScript Object Notation**.  
It’s a simple, easy-to-read way to store and organize **data**.

A JSON file might look like this:

<pre> ```json { 
    "name": "Jordan", 
    "grade": 11, 
    "interests": ["basketball", "coding", "music"] 
  } ``` </pre>

⬆️ This file stores:
- A name (`"Jordan"`)
- A grade (`11`)
- A list of interests

---
## 🗝️ Key Terms in JSON

### 🔑 Key-Value Pair

A **key-value pair** is like a label and its content.

Example:

"name": "Jordan"

- "name" is the key
- "Jordan" is the value

Together, they make a pair where...
- Key = what kind of info
- Value = the actual info

A JSON "object" is simply a group of key-value pairs, grouped inside of curly braces { }. 

---
### 📎 A Note on Indentation in JSON

When working with **JSON files**, indentation and line breaks make the file easier for **humans** to read — but they aren't necessary for the computer.

✅ These two are functionally **identical**:

<pre> ```json { 
    "name": "Jordan", 
    "grade": 11, 
    "interests": ["basketball", "coding", "music"] 
  } ``` </pre>

-and-

{"name":"Jordan","grade":11,"interests":["basketball","coding","music"]}

##👀 The second version is much easier for us to read because of:

- Line breaks

- Indentation

But remember:

What really matters is the structure — the organization into key-value pairs and objects.
JSON doesn't care about spaces or hard returns!

---

## 🎯 Why do we use JSON?

**JSON is built for structure.**  
It’s perfect when you want to keep track of data in a consistent, readable format — like a digital filing cabinet.

You’ll see JSON files used for:
- ✅ **Saving user information**
- ✅ **Storing AI prompt/response pairs**
- ✅ **Submitting work in a way that’s easy for scripts to process**
- ✅ **Moving data between systems (e.g. AI models, web apps)**

---

## 💡 Why does this matter for our class?

- JSON files help us **organize your work** so it can be:
  - 🔍 **Analyzed** by AI
  - 📦 **Stored** in GitHub
  - 🤖 **Graded** by automated tools
- They’re **easy to version**, so we can track what you submitted and when
- They help you **develop real-world tech skills** used in programming, data science, and app development

---

## 🧪 Try It

Can you create a `.json` file that includes:
- Your name  
- Your favorite food  
- One goal for this course  

📁 Name it "TD02_MY_JSON", and commit it to your repo.  

---
