# Theme Documentation

Welcome to the documentation for our theme! This guide will assist new developers in continuing the development of our theme. Here, you will find relevant information about the theme's features, files that may require editing, design decisions, colors, and more. This documentation assumes basic knowledge of WordPress theme development.

## Theme Overview

- We utilized VSCode as our preferred code editor for working with the theme folder.
- The theme is based on the Underscores starter theme, providing a solid foundation for customization.
- We opted to use SASS (Syntactically Awesome Style Sheets) as it offers a more efficient way to write CSS.

## Getting Started

To prepare your development environment, follow these steps:

1. Install the "Live Sass Compiler" extension in VSCode.
2. Configure the output CSS for the Sass file:
   - Go to **Settings**.
   - Select **Extensions**.
   - Find **Live Sass Compiler** and click on **Edit in settings.json** under **Formats**.
   - Replace `"savePath": null` with `"savePath": "../sass"`.
   - Save the changes.
   
![VSCode Settings](image.jpg)

By performing the above configuration, the Sass compiler will output the compiled CSS into the correct directory. Afterward, you only need to edit the `style.scss` file located in the Sass folder.

## Theme Features

- Responsive Design: The theme incorporates a responsive design, ensuring that the layout and content dynamically adjust to fit multiple screen sizes.

Feel free to explore the theme files, make necessary modifications, and extend its functionality to suit your needs. Happy coding!

WRITE MORE DETAILS ABOUT FTP TO LIVE SITE here