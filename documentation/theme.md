# Theme Documentation

Welcome to the documentation for our theme! This guide will assist new developers in continuing the development of our theme. Here, you will find relevant information about the theme's features, files that may require editing, design decisions, colors, and more. This documentation assumes basic knowledge of WordPress theme development.

## Theme Overview

- We utilized VSCode as our preferred code editor for working with the theme folder.
- The theme is based on the Underscores starter theme, providing a solid foundation for customization.
- We opted to use SASS (Syntactically Awesome Style Sheets) as it offers a more efficient way to write CSS.

## Getting Started

To prepare your development environment, follow these steps:

1. Install the "Live Sass Compiler" extension in VSCode.
![image](https://github.com/cp3402-students/project-the-hateful-eight/assets/88971553/f432cafa-b2d3-452f-b0e6-55c9e8a9d6b7)

2. Configure the output CSS for the Sass file:
   - Go to **Settings**.
   - Select **Extensions**.
   - Find **Live Sass Compiler** and click on **Edit in settings.json** under **Formats**.
   - ![image](https://github.com/cp3402-students/project-the-hateful-eight/assets/88971553/32e30f66-da86-4c62-97e9-1fea8fe89ad7)
   - Replace `"savePath": null` with `"savePath": "../sass"`.
   - ![image](https://github.com/cp3402-students/project-the-hateful-eight/assets/88971553/794af5cd-0f42-419d-9b2a-e4025c223e19)
   - Save the changes.
   
By performing the above configuration, the Sass compiler will output the compiled CSS into the correct directory. Afterward, you only need to edit the `style.scss` file located in the Sass folder.

## Theme Features

Our theme embraces a unique approach with intentionally simple and minimalistic design. We believe that simplicity can be a powerful aesthetic choice, allowing the content to take center stage. The deliberate lack of embellishments and intricate visual elements creates a clean and uncluttered look, focusing solely on delivering the core message of your website. Feel free to explore the theme files, make necessary modifications, and extend its functionality to suit your needs. Happy coding!

Key Features:

- Responsive Design: The theme incorporates a responsive design, ensuring that the layout and content dynamically adjust to fit multiple screen sizes.
- Minimalistic Design: Our theme follows a minimalistic design philosophy, eliminating unnecessary distractions and focusing on essential elements.
- Clean Typography: The typography is intentionally selected to be clean and straightforward, ensuring readability and clarity of the content.
- Subtle Color Palette: We have chosen a subtle color palette consisting of light blue and light orange. These colors create a soothing and harmonious visual experience, adding a touch of warmth without overpowering the simplicity of the design.
- Ample White Space: The generous white space surrounding the content provides breathing room and enhances the overall simplicity and clarity.
- Streamlined Layout: The layout is intentionally streamlined, avoiding complex structures and providing a straightforward and intuitive user experience.

By intentionally embracing simplicity, our theme encourages visitors to engage with your content without any visual distractions. It offers a refreshing and unpretentious online presence, letting your message speak for itself. Embrace the beauty of simplicity with our intentionally minimalistic theme.


## FTP from Local to Live Site with FileZilla

Before proceeding with the FTP transfer, make sure you have the following:

- FileZilla installed on your local machine. You can download it from the [official FileZilla website](https://filezilla-project.org/).
- FTP credentials for your live site. These are typically provided by your web hosting provider and include the FTP server address, username, and password.

Follow the steps below to transfer your local site files to the live site using FileZilla:

1. In the FileZilla interface, navigate to **File** > **Site Manager** to open the Site Manager window.
2. Click on the **New Site** button and give a name to your site (e.g., "Live Site").
3. Enter the FTP server details provided by your web hosting provider, and then click **Connect**:
   - **Host**: Enter the FTP server address.
   - **Port**: If a specific port is required, enter it; otherwise, leave it blank.
   - **Protocol**: Choose "FTP - File Transfer Protocol".
   - **Encryption**: Select "Use explicit FTP over TLS if available" for secure connections; otherwise, choose "Only use plain FTP".
   - **Logon Type**: Choose "Normal" for standard FTP authentication.
   - **User**: Enter your FTP username.
   - **Password**: Enter your FTP password.
   - ![image](https://github.com/cp3402-students/project-the-hateful-eight/assets/88971553/3af87058-01fe-471d-b7a2-6d96265c3c6c)
4. Once connected, the FileZilla interface will display your local machine's file directory on the left side and the remote server's directory on the right side.
   - ![image](https://github.com/cp3402-students/project-the-hateful-eight/assets/88971553/15a80906-7841-4175-9e7e-ad1d64eb7a3c)
5. Drag and drop the selected files and folders from the left side (local machine) to the right side (remote server) in the FileZilla interface.

It is essential to double-check the target directory on the live site and ensure that you are not overwriting any important files. Always perform a backup of your live site before proceeding with FTP transfers to avoid any potential data loss. After that, your changes should be reflected on the live site, allowing visitors to access the updated version of your website.
