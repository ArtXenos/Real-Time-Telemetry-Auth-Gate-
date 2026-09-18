# Real-Time-Telemetry-Auth-Gate-

Real-Time Telemetry (Auth Gate)
Core Task: Add a live character counter directly beneath the password field.
Mandatory Technique: Bind an 'input' event listener to the password field and update the textContent of a target <span> on every keystroke.

## DOM Logic
First, a paragraph element was added to the .html file to display the counter. Then, in the .js file, a global passLength variable was added to track password length. Then, an "input" event listener was added to the existing passwordInput element to get the length of its input every time something is typed into it. Finally, we update the paragraph element/counter each time an input is added to the passwordInput field.

### Members:
System Analyst - Cona, Mark Daniel
Frontend Developer - Elizan, Ramon Benedict
Quality Assurance - Guadalquiver, Art Xenos
