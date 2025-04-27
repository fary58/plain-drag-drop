# JavaScript Drag & Drop Project Manager 🏗️

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![DOM API](https://img.shields.io/badge/DOM-API-blue)
![Drag&Drop](https://img.shields.io/badge/Interaction-Drag_&_Drop-green)

A pure JavaScript implementation of a project management board with drag and drop functionality between "Active" and "Finished" project lists.

## Features ✨
- 📦 **Drag and Drop** projects between lists
- 🔄 **Dynamic Project Switching** (Active ↔ Finished)
- ℹ️ **Tooltip System** for additional project info
- ♻️ **Clean DOM Manipulation** with helper classes
- 🎯 **Event Delegation** for efficient handling

## How It Works 🔧
```javascript
// Example of the drag and drop implementation
list.addEventListener('drop', event => {
  const prjId = event.dataTransfer.getData('text/plain');
  document.getElementById(prjId).querySelector('button:last-of-type').click();
});
Key Components 🧩
DOMHelper: Utility class for DOM manipulation

ProjectItem: Manages individual project items

ProjectList: Handles lists of projects (Active/Finished)

Tooltip: Displays additional project information

Installation & Usage 🚀
Clone the repository

Open index.html in your browser

Interact with projects:

Drag between lists

Click "More Info" for details

Use buttons to switch status

Why This Project? 💡
Demonstrates pure JavaScript DOM manipulation

Implements native HTML5 Drag and Drop API

Shows clean class-based architecture

Perfect for learning core web concepts



### Key Description Points:
1. **Pure JavaScript Implementation** - No frameworks or libraries
2. **Native HTML5 Drag and Drop API** - Leverages browser capabilities
3. **Object-Oriented Structure** - Clean class organization
4. **Interactive Elements** - Buttons, tooltips, and drag handles
5. **Visual Feedback** - Smooth transitions and UI responses
