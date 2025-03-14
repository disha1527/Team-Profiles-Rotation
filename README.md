<h1>Team Profiles Rotation</h1>

<p>We’ll use HTML to structure the team profiles and CSS to style them and handle the rotation animation.</p>

<h1>HTML:</h1>
This HTML code creates a circular layout of team profiles that can be interacted with using radio buttons hidden from view.
Each profile is represented by a label containing an image and an SVG text element that displays the team member’s name and role. 
The labels are positioned in a circular arrangement around a central element that displays “The Team.” 
The circlePath SVG template is used to create circular text paths for the profile descriptions.
The accompanying CSS (not shown here) styles the layout and interactions, such as enlarging the image and showing additional details when a profile is selected.

<h1>CSS:</h1>
This CSS code styles a web page with a full-screen dark background and centered content. It hides radio inputs and uses labels inside a circular wrapper as clickable elements. 
The labels have a smooth transition effect, changing the scale of embedded images and SVGs when checked. There’s also a styled centered element and animated transformations for avatars arranged in a circular layout. 
The code includes various styling properties like borders, shadows, colors, and positioning to create a visually appealing interactive interface.

<h1>JS:</h1>
This JavaScript code selects all radio buttons on the page and adds a click event listener to each one. 
When a radio button is clicked, the event’s default action is prevented, and a timeout is set to toggle the checked state of the radio button. 
This effectively allows radio buttons to be unchecked by clicking on them.

Live Demo: https://disha1527.github.io/Team-Profiles-Rotation/

![Team Profiles rotation with pure CSS - Google Chrome 14-03-2025 17_54_34](https://github.com/user-attachments/assets/9588c5cd-fbaa-4b36-ba90-2c2becfe157b)

![Team Profiles rotation with pure CSS - Google Chrome 14-03-2025 17_54_07](https://github.com/user-attachments/assets/caf35b49-50b7-4d36-9065-eae9be782732)

