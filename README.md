# Password Toggle

This project implements a password visibility toggle feature using HTML, CSS, and JavaScript. It allows users to show or hide the password they are entering, enhancing usability and providing a convenient user experience.
<h2>Key Features</h2>
<h3>Password Visibility Toggle</h3>
<h4>Interactive Eye Icon</h4>
Users can click an eye icon next to the password input field to toggle the visibility of the password. The icon changes between an "eye-open" and "eye-close" state to indicate the current visibility. 
<h4>Dynamic Input Type Change</h4>
The password input field dynamically switches between "password" and "text" types, allowing users to view or hide the password as needed. 
<h2>Technical Overview</h2>
<h3>HTML Structure</h3>
The HTML file includes an input box containing a password field and an eye icon. The password field is initially set to "password" type, and the eye icon's image source is set to "eye-close.png". 
<h3>CSS Styling</h3>
<h4>Design and Layout</h4>
The CSS styles provide a clean and modern look. The input box is centered on the page, with a white background contrasting the dark purple page color. The eye icon is styled to be clickable and visually aligned with the input field. 
<h3>JavaScript Functionality</h3>
<h4>Password Toggle Function</h4>
The JavaScript file includes an event listener on the eye icon that toggles the input field's type between "password" and "text." It also updates the eye icon's image source to reflect the current state.

    eyeIcon.onclick = function () {
        //Function implementation
    }

<h2>In Summary</h2> 
This password toggle project offers a simple yet effective way to improve user experience when dealing with password fields. The interactive eye icon, combined with clean styling and straightforward functionality, makes the password entry process more user-friendly and accessible.
