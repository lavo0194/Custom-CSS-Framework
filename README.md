# Custom-CSS-Framework

Name:CraftCSS

Description:
A customizable CSS framework built with Sass, offering a consistent theme for HTML elements like buttons, forms, and tables, along with utility classes for common styling tasks. It’s easy to integrate, highly maintainable, and perfect for rapid web development.

Installation Instruction:
1.Clone the Repository: To use this CSS framework, first clone the repository from GitHub
2.Install Dependencies: This framework uses Sass, so you’ll need to install Sass if you haven't already. You can install it globally via npm
3.Compile the Sass Files: After installing Sass, compile the Sass files into a single CSS file. Run the following command inside the project directory
4.Link the Compiled CSS: Include the compiled styles.css file in your HTML project. Add this line to your <head> section 

Usage Instructions:
1.Import the Framework: You can include the framework into your project by linking the styles.css file, or if you're working with Sass, import the main Sass file (main.scss) into your project
2.Apply the Styles: Once you've linked or imported the compiled CSS file, you can start using the styles in your HTML.

Customization Instructions:
1.Change Colors: To change the primary color, modify the $primary-color variable in _variables.scss
2.Change Font Family: To use a different font, change the $font-family variable in _variables.scss
3.Adjust Spacing and Font Size: To adjust the base spacing or font size across the framework
4.Override Styles in Your Own Files: You can override the default styles in your own project-specific Sass files after importing the framework.
5.Compile After Customization: After making any changes to the _variables.scss file or any other Sass partial, don’t forget to recompile your Sass files