To-Do List Application Documentation

1. Overview

The To-Do List application provides users with a simple interface to manage their tasks. Users can add new tasks, mark tasks as completed, and remove tasks from the list. The application utilizes HTML, CSS, and JavaScript to create an interactive and responsive user experience.
2. HTML Structure (index.html)

    DOCTYPE Declaration: Specifies the document type and version.
    Root HTML Element: <html> element defines the root of the HTML document.
    Head Section: Contains metadata and links to external resources.
    Body Section: Contains the content of the web page.
        Container: <div class="container"> serves as the main container for the To-Do List application.
            Todo App Section: <div class="todo-app"> contains the To-Do List content.
                Heading: <h2> provides a title for the To-Do List.
                Input Section: <div class="row"> includes an input box and "Add Task" button.
                    Input Box: <input type="text" id="input-box" placeholder="Add your Text"> allows users to enter new tasks.
                    Add Task Button: <button onclick="addTask()">Add Task</button> triggers the addition of a new task.
                Task List: <ul id="list-container"> displays the list of tasks.
                    Task Items: <li> elements represent individual tasks.

3. CSS Styling (style.css)

    Global Styles: Defines global styles such as margins, paddings, and font family.
    Custom Properties: Defines custom properties for colors.
    Container Styles: Styles the main container for the To-Do List application.
    Header Styles: Styles the header section, including the title.
    Input Section Styles: Styles the input box and "Add Task" button.
    Task List Styles: Styles the task list and individual task items.
    Responsive Design: Implements responsive design using media queries for different screen sizes.

4. JavaScript Functionality (app.js)

    Add Task Function: addTask() adds a new task to the list when the "Add Task" button is clicked. It also validates the input box to ensure it is not empty.
    Save Data Function: saveData() saves tasks to the browser's local storage.
    Show Task Function: showTask() retrieves and displays tasks from local storage when the page loads.
    Event Listeners: Listens for clicks on list items and span elements within the list container to toggle task completion and remove tasks.

5. Additional Notes

    Local Storage: The application utilizes local storage to persist tasks, ensuring they are retained even after page reloads.
    Font: The application uses the "Poppins" font from Google Fonts for consistent typography.
    Author Information: The author information is displayed at the bottom of the page.

6. Conclusion

This documentation provides a comprehensive overview of the To-Do List application, including its structure, styling, functionality, and additional features. Users can refer to this documentation to understand how the application works and how they can interact with it.
