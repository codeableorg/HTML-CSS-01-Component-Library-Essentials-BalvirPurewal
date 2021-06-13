# Component Library - Essentials
While the concept of Design Systems is really important, our main focus as developers is to build and use a component library. Today assignment is to start building a basic component library using the concepts reviewed so far.

Find the design [here](https://www.figma.com/file/ij7FEIPE5bOWVMZBNt8fhk/Component-Library-Essentials?node-id=30%3A68).

## Take into consideration:
- Avoid using CSS Flexbox or CSS Grid for now. Stick to the Float positioning system.
- Organize your CSS files so your components could be re-use with ease. You could follow this structure:
![component-library file structure](./_readme_images/css_components.png)

  **index.html**: contain all the HTML for your main page (Disain page). This file links to the style.css file.

  **css/style.css**: this is the main css file for your project. Here live all the global CSS rules. It also imports the specific css files for each one of your components.

  **css/components/component.css**: Here live the specific css rules for one component.
  
Have fun and don't forget to ask for help when you get stuck.