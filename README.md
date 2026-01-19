# SQL IN Clause Converter

A lightweight web tool that converts multi-line input into a SQL-friendly `IN` clause — perfect for quick and easy list formatting during development or data querying.

🌐 **Live demo:** [https://sqlin.dmoruzzi.com](https://sqlin.dmoruzzi.com)

---

## 🚀 Features

- 🖊️ **Paste or type one item per line**  
  Supports any text input, one item per line.
- ⚡ **Instant conversion**  
  Automatically generates a SQL `IN` clause in the format `('item1', 'item2', 'item3')`.
- 📋 **Copy to Clipboard**  
  Copy the result with a single click.
- 🔄 **Auto-copy feature**  
  Optionally enable auto-copy when input changes.
- ❌ **Input validation**  
  Highlights invalid characters like single quotes (`'`) to prevent SQL errors.
- 🔒 **Runs entirely in your browser**  
  No data is sent to any server; fully client-side and private.

---

## 🛠️ Usage

1. Open the web app in your browser.
2. Paste or type your list of items into the text area (one per line).
3. The converted SQL `IN` clause will appear below the input in real-time.
4. Click **Copy to Clipboard** to copy the formatted result.

**Example:**

**Input:**

```
item1
item2
item3
```

**Output:**

```
('item1', 'item2', 'item3')
```

---

## ⚙️ Features in Detail

### 1. Auto-copy
Enable the auto-copy feature by clicking the **Enable AutoCopy** button. When enabled, the formatted SQL clause will automatically be copied to the clipboard whenever the input changes.

### 2. Error Handling
If your input contains invalid characters such as single quotes (`'`), the tool will display an error below the input:

```

Error: The following lines contain invalid characters: item'4, item'7

````

### 3. Persistent Settings
The auto-copy setting is saved in your browser’s local storage, so your preference persists across sessions.

---

## 📝 Installation (Optional)

This project is fully client-side, so no installation is required. Simply open the `index.html` file in a browser.  

If you want to host it yourself:

```bash
git clone https://github.com/dmoruzzi/sqlin.dmoruzzi.com.git
cd sqlin.dmoruzzi.com
# Open index.html in any browser
````

