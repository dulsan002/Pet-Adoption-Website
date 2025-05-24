# 🐾 Pet Adoption Website

A simple, dynamic pet adoption website built with HTML, CSS, and vanilla JavaScript. This project fetches data from an external JSON API and dynamically displays pet cards with filtering functionality.

## 🚀 Features

- 🔄 Fetches pet data from a live JSON API
- 📄 Uses HTML templates to dynamically generate content
- 🖼 Displays pet images, names, species, ages, and descriptions
- 🔍 Filter pets by type (All, Dogs, Cats, Rabbits)
- ✨ Active state styling for filter buttons

## 🧰 Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- JSON

## 📁 Project Structure

project/
├── index.html
├── style.css
└── script.js

## 📦 How It Works

1. **Fetches pet data** from:  
   `https://learnwebcode.github.io/pet-adoption-data/pets.json`

2. **Clones** an HTML template for each pet using JavaScript:
   ```html
   <template id="animal-card">...</template>


Populates the card with pet details including:

Name
Species
Age (calculated from birth year)
Description
Image
Adoption link

Filter buttons allow users to view:
  All pets
  Only Dogs
  Only Cats
  Only Rabbits

🎯 How to Use
Clone the repository or download the code.
Open index.html in a web browser.
Explore the pet cards and use the filter navigation.

🔧 Future Improvements (Optional Ideas)
Add a search bar for pet names
Add pagination or lazy loading
Add animations or transitions
Allow users to "favorite" pets
Implement an actual backend for form submissions

📝 License
This project is open-source and free to use for educational or personal purposes.

🙌 Acknowledgements
Pet data provided by learnwebcode


