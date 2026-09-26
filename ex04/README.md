 Experiment No. 04 - Dynamic DOM Manipulation

 Objective

Develop a dynamic webpage where elements are added, removed, or modified using the DOM model and event handling.

Information

This experiment demonstrates how JavaScript can be used to dynamically manipulate HTML elements through the **Document Object Model (DOM)**.

The webpage contains three buttons that perform different DOM operations:

- **Add Element** – Creates a new paragraph and adds it to the webpage.
- **Remove Element** – Removes the last element from the container.
- **Modify Element** – Changes the text, color, and font style of the first paragraph.

 Technologies Used

- HTML5
- CSS3
- JavaScript
- DOM Manipulation
- Event Handling

 Program Description

The HTML file contains a simple webpage with a heading, three buttons, and a container containing an initial paragraph.

JavaScript functions are used to perform DOM operations:

`addElement()`

Creates a new `<p>` element using `document.createElement()` and adds it to the container using `appendChild()`.

`removeElement()`

Selects the container and removes its last child using `removeChild()`.

`modifyElement()`

Selects the first paragraph using `getElementById()` and changes its text, color, and font weight.


DOM Methods Used

- `document.createElement()`
- `document.getElementById()`
- `appendChild()`
- `removeChild()`
- `textContent`
- `style.color`
- `style.fontWeight`

Event Handling

The buttons use the `onclick` event to execute JavaScript functions.

```text
Add Element     → addElement()
Remove Element  → removeElement()
Modify Element  → modifyElement()


How to Run

Download or clone the repository.
Open the project folder.
Open index.html in a web browser.
Click the buttons to observe the DOM changes.
Expected Output

The webpage displays:

A Dynamic DOM Manipulation heading.
An Add Element button.
A Remove Element button.
A Modify Element button.
A container containing the initial paragraph.

When the buttons are clicked, the webpage is updated dynamically without refreshing the page.

Result

Thus, a dynamic webpage was successfully developed using JavaScript DOM manipulation and event handling. Elements were successfully added, removed, and modified dynamically.

Author

Nalabolu Pavani | AIDS - III year | IFET College Of Engineering

