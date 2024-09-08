# Recipe Finder

The **Recipe Finder** is a simple website that allows users to search for various meal recipes based on ingredients they provide. It fetches data from the **Edamam API** to display a list of meals, and users can click on any meal to view its details and get the recipe. This website is built with HTML, CSS, and JavaScript, providing a smooth and intuitive user experience with a clean interface.

## Technologies Used

- **HTML**: For structuring the web pages.
- **CSS**: For styling and designing the user interface.
- **JavaScript**: For the core functionality, including fetching data from the API and handling user interactions.
- **Edamam API**: For retrieving meal recipes based on user input.

## Project Structure

The project consists of the following files:
- **index.html**: The main HTML file that contains the structure of the webpage.
- **style.css**: The CSS file for styling the web page, ensuring a clean and modern look.
- **script.js**: The JavaScript file responsible for the dynamic features, such as fetching recipes from the API, displaying search results, and showing detailed recipe information.
- **bg.jpeg**: A background image used to enhance the aesthetics of the webpage.

### File Descriptions:

- **bg.jpeg**: The background image file for the web app.
- **index.html**: The entry point for the web app, which includes the search bar and recipe display area.
- **script.js**: Contains the JavaScript code for fetching and displaying recipes based on user input.
- **style.css**: The file where all the CSS rules for the layout and design are written.

## How to Execute

1. **Clone the Repository**:
2. **Open the Project**:
   Navigate to the folder where the project is located and open `index.html` in your browser.
3. **API Key Setup**:
   - If required, you will need an API key from Edamam. You can get one by signing up at [Edamam's API portal](https://developer.edamam.com/).
   - After obtaining your API key, update the `script.js` file with your Edamam API key:
     ```javascript
     const app_id = 'YOUR_APP_ID';
     const app_key = 'YOUR_APP_KEY';
     ```
4. **View the Application**:
   Open `index.html` in your preferred web browser. Use the search bar to find recipes based on the ingredients you provide, and enjoy exploring new meal ideas.

![Screenshot 2024-06-17 184840](https://github.com/manvithapula/recipe-finder/assets/113161233/6285855d-fc57-41e9-851c-ccf8f6a5d7f4)
![Screenshot 2024-06-17 184859](https://github.com/manvithapula/recipe-finder/assets/113161233/ea922b69-254a-4291-87b7-41734331647f)
![Screenshot 2024-06-17 184915](https://github.com/manvithapula/recipe-finder/assets/113161233/9791cc4a-e8d3-4e92-a0e7-260c0267f0b6)
