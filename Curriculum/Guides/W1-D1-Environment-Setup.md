# Week 1 Day 1 - Environment Setup

This guide explains three complete ways to run JavaScript for this lab. Pick the method that matches your device and comfort level. You can switch between them anytime.

---

## Method 1: Run JavaScript in the Browser Console (Fastest)

Use this when you just want to test small snippets or understand basic syntax.

### Step 1: Open a browser
- Use Chrome, Edge, or Firefox.

### Step 2: Open Developer Tools
- **Windows:** Press `Ctrl + Shift + I` (or `F12`)
- **Mac:** Press `Cmd + Option + I`

### Step 3: Open the Console tab
- Click the **Console** tab.

### Step 4: Run your first JS code
Type this and press Enter:
```javascript
console.log("Hello, JavaScript!");
```

### Step 5: Practice more commands
```javascript
2 + 3
Math.sqrt(49)
let name = "Asha";
console.log(`Hi, ${name}`);
```

**Pros:** No setup, instant feedback.
**Cons:** Code is not saved unless you copy it out.

---

## Method 2: Run JavaScript with Node.js (Recommended for Assignments)

This method lets you write full programs in `.js` files and run them from the terminal.

### Step 1: Install Node.js
- Go to https://nodejs.org
- Download the **LTS** version.
- Run the installer and keep default settings.

### Step 2: Verify installation
Open a terminal:
- **Windows:** Start Menu -> type `PowerShell` -> open it
- **Mac:** Open **Terminal**

Run:
```
node --version
```
You should see a version like `v18.x.x` or higher.

### Step 3: Create a folder for your lab work
Example:
```
BCA-ClientSideScripting
```

### Step 4: Create a JS file
In VS Code:
1. Open the folder.
2. Create a file: `Week1_Day1_HelloWorld.js`
3. Add this code:
```javascript
console.log("Hello World");
```

### Step 5: Run the file
Open the integrated terminal in VS Code (`Ctrl + `) and run:
```
node Week1_Day1_HelloWorld.js
```

**Pros:** Best for assignments, works with files, repeatable.
**Cons:** Requires Node.js installation.

---

## Method 3: Run JavaScript in an HTML File (Browser + File)

This method is useful when you want to prepare for web development and later DOM work.

### Step 1: Create an HTML file
Create a file named `index.html` and add:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>JS Practice</title>
</head>
<body>
    <h1>JavaScript Practice</h1>

    <script>
        console.log("Hello from HTML");
        alert("Welcome to JS!");
    </script>
</body>
</html>
```

### Step 2: Open it in a browser
- Double-click the file or drag it into Chrome/Edge.

### Step 3: View output
- Alerts appear on the page.
- `console.log` appears in Developer Tools -> Console.

**Pros:** Bridges into real web development.
**Cons:** Requires HTML setup and refresh to see changes.

---

## Optional: Use GitHub Codespaces (If You Have Student Benefits)

If you have GitHub Student Developer Pack access, you can use **GitHub Codespaces** and avoid installing anything on your computer.

### Step 1: Activate Student Benefits
- Visit https://education.github.com/pack
- Apply and wait for approval.

### Step 2: Open your GitHub Classroom repository
- Go to your assignment repository on GitHub.

### Step 3: Create a Codespace
- Click the green **Code** button.
- Choose **Codespaces** -> **Create codespace on main**.

### Step 4: Run JavaScript in the Codespace
- Open the terminal inside Codespaces.
- Run a file the same way:
```
node Week1_Day1_HelloWorld.js
```

### Step 5: Save your work
- Use Git commands or VS Code source control to commit and push your changes.

**Why use Codespaces?**
- No installation
- Same environment everywhere
- Good for slow laptops or lab machines

---

## Quick Recommendation for Week 1
- Use **Method 1** for quick tests.
- Use **Method 2** for assignments.
- Try **Method 3** if you want to explore web development.
- Use **Codespaces** if your device is slow or you want zero setup.
