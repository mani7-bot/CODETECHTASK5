**<ins>Name</ins>:-** VANA MANIKANTA

**<ins>COMPANY</ins>:-** CODTECH IT SOLUTION

**<ins>ID</ins>:-** CT12DS2505

**<ins>DOMAIN</ins>:-** FRONTEND

**<ins>DURATION</ins>:-** SEPTEMBER 20th,2024 to NOVEMBER 20th,2024

**<ins>Mentor</ins>:-** Neel Santhosh Kumar

# <ins>Project Name</ins> :- RECIPE FINDER

### Overview of the Code

This code represents the structure of a **Food Recipe Finder** web application that allows users to search for food recipes based on ingredients or food names.

#### HTML Structure:
1. **DOCTYPE and HTML Basics**: The document is an HTML5 document, declared by `<!DOCTYPE html>`, and it uses the `lang="en"` attribute to specify the language as English.

2. **Head Section**:
   - **Meta Tags**: 
     - The `meta charset="UTF-8"` tag ensures proper character encoding for the page.
     - The `meta name="viewport"` tag enables responsive design by adjusting the layout on different screen sizes.
   - **Title**: The page title is set to "Food Recipe Finder", which appears in the browser tab.
   - **Stylesheet**: A `link` element includes an external CSS file (`style.css`) for styling the page.

3. **Body Section**:
   - **Main Wrapper (`div.main`)**: Contains the core content of the page.
     - **Heading**: The main heading (`<h1>`) displays the title of the app, "Food Recipe Finder".
   
   - **Search Section**: This is a container for the search input field.
     - **Search Box**: A `div` with the class `search-box` contains an input field (`<input>`) where users can type the name of a food or ingredient they want to search for. The input field has the `id="searchInput"` for identifying it.
     - **Search Button**: The button with the `id="searchButton"` triggers the search when clicked. It contains an SVG icon representing a search (magnifying glass) inside a button (`<button>`). The button allows users to initiate a search for recipes.

   - **Recipe Result Section**: After a user performs a search, the matching results will appear in an unordered list (`<ul>`) with the `id="results"`. Each recipe will likely be displayed as a list item within this section (though the actual recipe rendering logic is handled by the JavaScript file).

4. **JavaScript File**: The `script.js` file is linked at the bottom of the body, indicating that the page's behavior (such as the search functionality and displaying results) will be handled by this external JavaScript file.

#### Functionality (Implied by the Code):
- **Search Feature**: Users can input a food item or ingredient in the text field and click the search button to look for relevant recipes.
- **Dynamic Results**: The list of recipe results (`<ul id="results">`) will be dynamically populated with search results, likely through JavaScript interacting with an API or local data.
- **Responsive Design**: The meta viewport tag ensures the app is responsive and adjusts well across different devices like mobile phones and desktops.

The app aims to help users find food recipes based on their search queries, providing a user-friendly interface for browsing recipes by ingredients or dish names. The visual design and interaction will be styled using the external `style.css`, while the logic for fetching and displaying recipes will be handled by the `script.js` file.

