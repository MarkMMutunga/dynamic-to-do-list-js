# Dynamic To-Do List Application

A dynamic, interactive To-Do List application built with vanilla JavaScript, HTML, and CSS. This project demonstrates advanced DOM manipulation techniques, event handling, and modern web development practices.

## Features

- ✅ Add new tasks dynamically
- ❌ Remove tasks with a single click
- ⌨️ Add tasks using Enter key
- 🎨 Modern, responsive UI design
- 🔄 Real-time DOM updates

## Learning Objectives

This project helps you master:

- **Advanced DOM Manipulation**: Dynamic element creation and manipulation
- **Event Handling**: Click events, keyboard events, and user interactions
- **JavaScript Best Practices**: Clean code structure and error handling
- **Responsive Design**: Mobile-friendly CSS layouts

## What is DOM?

**DOM** stands for **Document Object Model**:

- **D** - **Document** = Your HTML webpage
- **O** - **Object** = Each HTML element becomes a JavaScript object
- **M** - **Model** = The structured representation/framework that organizes everything

The DOM is a programming interface that represents your HTML document as a collection of objects that JavaScript can manipulate. It's like a live bridge between your HTML and JavaScript, allowing you to:

- Find elements: `document.getElementById('task-input')`
- Create elements: `document.createElement('li')`
- Modify content: `element.textContent = 'Hello'`
- Add/remove elements: `parent.appendChild(child)`
- Handle events: `element.addEventListener('click', function)`

In this To-Do List app, DOM manipulation makes it "dynamic" - you can add and remove tasks without refreshing the page!

## Project Structure

```
dynamic-to-do-list-js/
├── index.html          # Main HTML structure
├── styles.css          # CSS styling and layout
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## Getting Started

1. **Clone or download** this repository
2. **Open** `index.html` in your web browser
3. **Start adding tasks** to your to-do list!

### Running the Application

#### Option 1: Direct File Opening
- Navigate to the project folder
- Double-click `index.html` to open in your default browser

#### Option 2: Live Server (Recommended for Development)
If you have VS Code with Live Server extension:
1. Right-click on `index.html`
2. Select "Open with Live Server"
3. The application will open in your browser with hot reload

#### Option 3: Local Web Server
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## How to Use

1. **Add a Task**: Type your task in the input field and either:
   - Click the "Add Task" button
   - Press the Enter key

2. **Remove a Task**: Click the red "Remove" button next to any task

3. **Input Validation**: The app will alert you if you try to add an empty task

## Technical Implementation

### DOM Manipulation Techniques Used

- `document.getElementById()` - Element selection
- `document.createElement()` - Dynamic element creation
- `appendChild()` - Adding elements to the DOM
- `removeChild()` - Removing elements from the DOM
- `addEventListener()` - Event handling

### Event Handling

- **Click Events**: Add button and remove buttons
- **Keyboard Events**: Enter key support for task input
- **DOMContentLoaded**: Ensures script runs after HTML loads

### Code Structure

The JavaScript follows a clean, organized structure:

1. **Setup**: DOMContentLoaded event listener
2. **Element Selection**: Getting references to DOM elements
3. **Core Function**: `addTask()` function with validation
4. **Event Binding**: Attaching event listeners

## Browser Compatibility

This application works in all modern browsers:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Future Enhancements

Potential improvements you could add:

- [ ] Local Storage persistence
- [ ] Task editing functionality
- [ ] Task completion status (checkboxes)
- [ ] Task categories or tags
- [ ] Drag and drop reordering
- [ ] Due dates and reminders
- [ ] Dark mode toggle
- [ ] Export/import functionality

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

Created by Mark Mikile Mutunga.

---

**Happy Coding!** 🚀
