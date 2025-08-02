<img width="3188" height="1202" alt="frame (3)" src="https://github.com/user-attachments/assets/517ad8e9-ad22-457d-9538-a9e62d137cd7" />


# CATMOSPHERE 🎯


## Basic Details
### Team Name: Bitbybit


### Team Members
- Team Lead: ANJU V B - TKMCE
- Member 2: IRENE TREESSA RAJ - TKMCE
-

### Project Description
   Catmosphere is a playful and whimsical web app where users can type or select the classic "meow" and discover what mood a virtual cat is in. With a single allowed input—"meow"—the app humorously interprets the cat’s emotions, ranging from sleepy to dramatic. Upon submission, it randomly redirects users to a mood display page showing a fun, quirky cat reaction.

This app combines HTML, CSS, and JavaScript for interactivity, animations, and a delightful user experience. Ideal as a light-hearted project or a creative showcase of DOM manipulation and user input handling.

DEPLOYED LINK: https://catmosphere.vercel.app/index.html

### The Problem (that doesn't exist)
Find out what the cat have to say when it meows..

### The Solution (that nobody asked for)
Made a website that shows what the cat feels through his meows

## Technical Details
### Technologies/Components Used
For Software:
- HTML
- CSS
- JS



### Implementation
For Software:
# Installation
 Option 1: Use Python (no need for Node.js)
bash
Copy
Edit
# In your project folder:
python -m http.server 8000
🔗 Then open: http://localhost:8000 in your browser.

✅ If you're using Node.js / want npm setup
If you want to set it up like a modern dev project (useful for deploying or future expansions), follow these steps:

🟢 1. Initialize npm
bash
Copy
Edit
npm init -y
🟢 2. Install a simple HTTP server
bash
Copy
Edit
npm install -g serve
🟢 3. Run the server
bash
Copy
Edit
serve .
🔗 Opens your project at http://localhost:3000 by default.

✅ If you're using VS Code
Use the Live Server extension:

Install Live Server

Right-click index.html → Open with Live Server

# Run
Option 1: Using Python (Easiest for static sites)
Step-by-step:

bash
Copy
Edit
cd path/to/your/project
python -m http.server 8000
🔗 Then open: http://localhost:8000

✅ Option 2: Using Node.js + serve
If you have Node.js installed:

bash
Copy
Edit
npm install -g serve
cd path/to/your/project
serve .
🔗 Then open: http://localhost:3000

✅ Option 3: Using Live Server in VS Code
Open your project folder in VS Code

Install the extension: Live Server

Right-click index.html → Click "Open with Live Server"

❗ Replace path/to/your/project with the actual folder path
Example (Windows command prompt):

bash
Copy
Edit
cd C:\Users\irene\Desktop\catmosphere
python -m http.server 8000

### Project Documentation
For Software:
 DEPLOYED LINK: https://catmosphere.vercel.app/index.html
 GITHUB LINK: https://catmosphere.vercel.app/index.html

# Screenshots (Add at least 3)
 https://drive.google.com/file/d/1UKns2dMJ-ATHWb8rojdwVxcssmWpRXnN/view?usp=sharing

 https://drive.google.com/file/d/1WPORjP-exlq354RHtCtD1Ez2ZkUKcMUr/view?usp=sharing




# Schematic & Circuit


   [User Interface (index.html)]
             |
             ▼
   [User selects a "meow" variant]
             |
             ▼
[JavaScript Validates Meow Input (script.js)]
             |
     ┌──────Yes────────┐
     |                 |
   Invalid?        [Random Mood Index Generator]
     |                 |
     ▼                 ▼
[Alert "Only meow allowed"]  [Redirect to mood.html?mood=X]
                                |
                                ▼
                  [mood.html loads with mood.js]
                                |
                                ▼
          [mood.js reads ?mood=X from URL]
                                |
                                ▼
        [Matches mood index to moods[] array]
                                |
                                ▼
         [Displays corresponding mood message]



### Project Demo
# Video
https://drive.google.com/file/d/1kU3cU0ULBpSkMmglSRh_iyfxK1RkXn3j/view?usp=sharing


## Team Contributions
- ANJU VB : worked on HTML and JSS
- IRENE TREESSA RAJ:worked on JS
- 
- 

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--25-25?link=https%3A%2F%2Fwww.tinkerhub.org%2Fevents%2FQ2Q1TQKX6Q%2FUseless%2520Projects)



