# On-Screen-Keyboard
An on-screen keyboard is a virtual keyboard that allows users to input text without using a physical keyboard. This can be useful in situations where a physical keyboard is not available or for users with limited mobility.

Key Concepts

Before using understand some key concepts:

    DOM Manipulation: The Document Object Model (DOM) is a programming interface for HTML and XML documents. It represents the structure of a web page and allows JavaScript to interact with the elements on the page.

    Event Handling: JavaScript provides event handling mechanisms to respond to user actions or system events. We can attach event listeners to elements and define functions to be executed when the event occurs.

    CSS Styling: Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML. We can use CSS to style our on-screen keyboard and make it visually appealing.

Code Structure

The code provided is structured using an object-oriented approach. It defines a Keyboard object with various properties and methods to create and control the on-screen keyboard.

The Keyboard object has the following structure:

    elements: Contains references to the main elements of the keyboard.
    eventHandlers: Contains event handler functions for input and close events.
    properties: Stores the current value of the keyboard input and the state of the caps lock.
    init(): Initializes the keyboard by creating the necessary elements and attaching event listeners.
    _createKeys(): Generates the HTML structure for the keyboard keys based on a predefined layout.
    _triggerEvent(handlerName): Triggers the specified event handler function.
    _toggleCapsLock(): Toggles the state of the caps lock and updates the keyboard keys accordingly.
    open(initialValue, oninput, onclose): Opens the keyboard and sets the initial value and event handlers.
    close(): Closes the keyboard and resets the value and event handlers.
