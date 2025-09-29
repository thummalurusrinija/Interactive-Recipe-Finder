# Interactive Recipe Finder

A simple and interactive web application that helps users discover delicious recipes based on the ingredients they have at home. Built with vanilla HTML, CSS, and JavaScript, this app leverages the Spoonacular API to find recipes that match your available ingredients.

## Features

- **Ingredient-Based Search**: Enter the ingredients you have, separated by commas, to find matching recipes
- **Recipe Cards**: View recipe results in an attractive card layout with images
- **Recipe Details**: See cooking time, serving size, used ingredients, and missing ingredients for each recipe
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Error Handling**: Graceful error messages for API failures or invalid inputs
- **Loading States**: Visual feedback during API requests

## Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for API calls

## Setup Instructions

1. **Clone or Download**: Download the project files to your local machine
2. **Open in Browser**: Simply open `index.html` in your web browser
3. **No additional setup required** - all dependencies are included in the single HTML file

## Usage

1. **Enter Ingredients**: In the input field, type the ingredients you have available, separated by commas (e.g., "chicken, rice, tomatoes, onions")
2. **Search Recipes**: Click the "Find Recipes" button or press Enter to search
3. **View Results**: Browse through the recipe cards that appear below
4. **Recipe Information**: Each card shows:
   - Recipe image
   - Title
   - Cooking time and serving size
   - Ingredients you have (used)
   - Ingredients you're missing

## API Key Setup

The application currently uses a Spoonacular API key that's hardcoded in the JavaScript. For production use or if you encounter API limits:

1. Sign up for a free API key at [Spoonacular API](https://spoonacular.com/food-api)
2. Replace the `apiKey` variable in the `<script>` section of `index.html` with your own key

```javascript
const apiKey = 'your_api_key_here';
```

## Project Structure

```
Interactive Recipe Finder/
├── index.html          # Main application file (HTML, CSS, JS)
├── TODO.md             # Project completion checklist
└── README.md           # This file
```

## Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling and responsive design
- **JavaScript (ES6+)**: Functionality and API integration
- **Spoonacular API**: Recipe data source

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request


## Acknowledgments

- Recipe data provided by [Spoonacular API](https://spoonacular.com/food-api)
- Icons and styling inspired by modern web design principles
      
