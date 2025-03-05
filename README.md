# Tweet Feed App

## Overview
This project is a simple **Tweet Feed App** that allows users to create, like, retweet, and reply to tweets dynamically. It is implemented using vanilla JavaScript and provides an interactive user experience.

## Features
- **Post new tweets** with a unique identifier.
- **Like and unlike tweets** by clicking the heart icon.
- **Retweet and un-retweet tweets** using the retweet icon.
- **Reply to tweets** and toggle replies visibility.
- **Live feed rendering** without page refresh.

## Technologies Used
- **JavaScript (ES6)** for handling interactions and data management.
- **HTML & CSS** for structuring and styling the UI.
- **Font Awesome** for icons.
- **UUID library** (imported from `jspm.dev`) for generating unique tweet IDs.

## Installation & Setup
1. Clone or download the repository.
2. Ensure you have a local web server (e.g., Live Server for VS Code) to serve the HTML file.
3. Open `index.html` in a browser to interact with the app.

## How It Works
1. **Tweet Creation:**
   - Users can type a tweet and post it by clicking the **Tweet** button.
   - The new tweet appears at the top of the feed.
2. **Like & Retweet Functionality:**
   - Clicking the heart icon toggles the like state.
   - Clicking the retweet icon toggles the retweet state.
3. **Reply Feature:**
   - Clicking the reply icon toggles the visibility of the reply section for a tweet.
4. **Dynamic Rendering:**
   - The UI updates dynamically when actions occur.

## Project Structure
```
📂 Tweet Feed App
├── 📄 index.html  # Main HTML file
├── 📄 index.js    # JavaScript logic for tweet interactions
├── 📄 data.js     # Tweet data storage (imported in index.js)
├── 📄 index.css   # Stylesheet for UI styling
├── images
   ├── Add all the images, I haven't gotten around to figure that part out yet
```

## Dependencies
- **UUID** for unique tweet identifiers (imported from `https://jspm.dev/uuid`).
- **Font Awesome** for icons.

## License
This project is open-source and available for modification and distribution.

