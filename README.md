# Color-Picker

### Project Description:
The Color Picker project is a simple web-based application that allows users to select a color, save their selection using cookies, and then display the selected color as the background of a subsequent page. This project demonstrates the use of HTML forms, PHP for server-side processing, and cookies for maintaining user preferences.

#### Files and Descriptions:

### File Name: `index.php`

### Description:
This page provides a form for users to select a color using an HTML color input. When the form is submitted, the selected color is saved in a cookie, and the user is redirected to `dex.php`.

#### Key Features:
- **Color Input**: Allows users to choose a color.
- **Form Submission**: Saves the selected color in a cookie and redirects to `dex.php`.
- **Styling**: Utilizes Bootstrap for a responsive and visually appealing form.

### File Name: `dex.php`

### Description:
This page retrieves the color saved in the cookie and sets it as the background color of the page. It also displays a message showing the selected color.

#### Key Features:
- **Cookie Retrieval**: Retrieves the color value from the cookie.
- **Dynamic Styling**: Applies the retrieved color as the background color of the page.
- **User Feedback**: Displays a message indicating the chosen color.
