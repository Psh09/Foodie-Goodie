# Foodie-Goodie App

The **Foodie-Goodie App** is a React-based web application that provides users with a collection of food recipes. Users can explore various recipes, which are fetched from an external API, and view detailed information about each recipe.

## Features
- Fetch and display food recipes from the Edamam API.
- Use React hooks (`useEffect`, `useState`) to manage state and component lifecycles.
- Render recipes in a user-friendly component structure.
- Display detailed information for each recipe, including ingredients, nutritional values, and preparation steps.

## Approach
The following outlines the approach to building the Foodie-Goodie App:

1. **Component Structure**: Design a React component structure that supports fetching, storing, and displaying food recipes.
   - Create a parent component that handles API calls and state management.
   - Create child components to display recipe details.

2. **API Integration**: Fetch food recipe data from an external API (Edamam) and integrate it into the app.
   - Use the Edamam Recipe Search API to fetch a list of recipes.
   - Store the fetched data in React's `useState` to dynamically update components.

3. **State Management**: Utilize React hooks to manage component state and side effects.
   - Use `useState` to store fetched recipes.
   - Use `useEffect` to trigger API calls when the component mounts or when dependencies change.

4. **Display Recipes**: Develop a user interface to display food recipes.
   - Use a component-based structure to create a clean and modular layout.
   - Implement filtering or search functionality to refine the displayed recipes.

## Getting Started
To get started with the Foodie-Goodie App, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.
   ```bash
   git clone https://github.com/Psh09/Foodie-Goodie.git
2. **Install Dependencies**: Navigate to the project folder and install the required dependencies.
   ```bash
    cd Foodie-Goodie
    npm install
          
3. **Obtain an API Key**: To fetch food recipes, you'll need an API key from the Edamam platform. Sign up at Edamam.
  Set Up the Environment Variables: Create a .env file in the project root and add your API key. Ensure the .env file is listed in .gitignore to avoid exposing sensitive information.
     ```bash
    REACT_APP_EDAMAM_API_KEY=your_api_key_here

4. **Run the App**: Start the development server to run the app locally.
    ```bash
    npm start

## Contributing
Contributions are welcome! If you'd like to contribute, fork this repository, create a new branch for your changes, and submit a pull request.

## Acknowledgments
Thanks to Edamam for providing the food recipe API.
