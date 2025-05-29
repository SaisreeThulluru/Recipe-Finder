# 🥘 Recipe Finder App

A beautiful desktop app built with **Python and Tkinter** that helps users discover recipes based on ingredients they already have. It uses the **Spoonacular API** to fetch real-time recipe data, along with images and clickable links.

---

## 🚀 Features

- Clean and modern UI using Tkinter with a background image
- Enter multiple ingredients (comma-separated)
- Fetches real-time recipe data using the Spoonacular API
- Displays recipe title, image, and a clickable link to full instructions
- Uses Pillow to render images in the GUI

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Tkinter** (built-in for GUI)
- **Pillow (PIL)** — for image handling
- **Requests** — for API calls
- **Spoonacular API** — for recipe data

---

### 📦 Installation & Setup

### 1. Clone this Repository
git clone https://github.com/SaisreeThulluru/recipe-finder-app.git
cd recipe-finder-app

### 2. Install Required Packages
Make sure you have Python installed, then install the required libraries:
pip install requests pillow

### 3. Get a Spoonacular API Key
Go to Spoonacular and sign up.
Copy your API key and paste it in the code:
API_KEY = 'YOUR_API_KEY_HERE'

### 4. Set Your Background Image Path How to Run
Replace the image path in this line with the correct location of your background image:

bg_image = Image.open(r"your/path/to/background.jpg")

### ▶️ How to Run 
python recipe_app.py

### ✏️ How to Use 
1.Launch the app (it will open in a full-screen window).

2.Enter a list of ingredients, separated by commas (e.g., egg, tomato, onion).

3.Click the Search button.

4.The app will:
Show a recipe title
Display an image of the recipe
Include a clickable link to the full recipe page
