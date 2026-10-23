# BurpXtract (XML Viewer)
BurpXtract (XML Viewer) is a Burp Suite extension that allows you to import .xml files (exported HTTP history from Burp) and view them as fully interactive request/response entries — just like Burp's native proxy tab.

![Built for Burp Suite](https://img.shields.io/badge/Built%20for-Burp%20Suite-orange?style=for-the-badge)
![Made with AI](https://img.shields.io/badge/Made%20with-AI-blueviolet?style=for-the-badge)
![Status](https://img.shields.io/badge/status-First%20Release-success?style=for-the-badge)
![Java](https://img.shields.io/badge/language-Java-blue?style=for-the-badge)

> **Import Burp XML logs like a boss.**  
> View, filter, sort, and replay them — as if they never left your proxy tab.

---

## 🧠 What is BurpXtract?

**BurpXtract** is a Burp Suite extension that **resurrects your exported HTTP history** from XML files and displays them like Burp's native proxy tab.
*Designed specifically for Burp Community users who want to save and revisit their crucial HTTP history beyond the session limits.*


This tool is made for you. ⚔️

---

## 🔥 Features

| Feature | Description |
|--------|-------------|
| 📂 XML Import | Import `.xml` files exported from Burp (HTTP history format) |
| 🧠 Smart Parsing | Auto-extracts Host, URL, Method, Status, MIME, Size, Timestamp |
| 📊 Sortable Columns | Click any column to sort (like native Burp history) |
| 🔍 Filter Requests | Search GET, POST, status codes, MIME types, and more |
| 💥 Send to Tools | Right-click → Send to Repeater or Intruder |
| 🧼 Clear History | Instantly clear parsed entries from view |
| 🎨 Native UI | Seamless integration with Burp's UI |

---

## 📸 Workflow

![Demo](https://github.com/pwn0clock/BurpXtract/blob/main/workflow.gif)


---

## 🚀 How to Use

### Directly Load the extension
1. Downlod the BurpXtract,jar
2. Load the extension in Burp Suite: Open Burp ==> Go to Extensions > Add ==> Select BurpXtract.jar ==> Click Next

### 💻 Install from Source
1. Clone this repo:
   ```bash
   git clone https://github.com/pwn0clock/BurpXtract/
2. Download the latest version of Burp Suite (Community Edition). Place the downloaded JAR (e.g., burpsuite_community.jar) inside the BurpXtract directory
3.Make sure Java 21 or later is installed:
   ```bash
   java -version
4. Compile the Java source code:
   ```bash
   javac -cp src/burpsuite_community.jar -d out src/burp/*.java
5. Package the compiled classes into a JAR:
   ```bash
   jar cf BurpXtract.jar -C out . 
6. Load the extension in Burp Suite: Open Burp ==> Go to Extensions > Add ==> Select BurpXtract.jar ==> Click Next
   
