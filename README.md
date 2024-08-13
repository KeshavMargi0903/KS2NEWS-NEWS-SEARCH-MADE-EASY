 KS2NEWS

**KS2NEWS** is a responsive web application that allows users to search and browse news articles from various sources. Users can filter news by categories such as Tech, Food, Movies, and Business. The app is built using HTML, CSS, and JavaScript, and it fetches data from the [News API](https://newsapi.org/).

## Features

- **Responsive Design**: Fully responsive layout, providing a seamless experience across all devices.
- **Search Functionality**: Search for news articles by typing keywords.
- **Category Filters**: Quickly filter news by predefined categories like Tech, Food, Movies, and Business.
- **Dynamic Content**: Fetches and displays the latest news articles in real-time using the News API.
- **Clean UI**: Simple and intuitive user interface with a focus on usability.

## Tech Stack

- **HTML5**: Markup language for structuring the content.
- **CSS3**: Styling with custom styles and media queries for responsiveness.
- **JavaScript**: Fetch API for data retrieval and DOM manipulation.
- **News API**: External API used to fetch news data.

## Installation

To run the KS2NEWS project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/KeshavMargi0903/KS2NEWS.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd KS2NEWS
   ```

3. **Open the `index.html` file in your browser:**

   ```bash
   open index.html
   ```

## Usage

- **Search for News**: Use the search bar to type in any keyword and hit enter. The app will display news articles related to the keyword.
- **Filter by Category**: Click on any category (Tech, Food, Movies, Business) to filter the news articles displayed.
- **Mobile Menu**: On smaller screens, use the hamburger menu to access categories and the search bar.

## API Key

The project uses the News API to fetch news articles. To use the application, you need to add your own API key:

1. Visit the [News API website](https://newsapi.org/) to obtain an API key.
2. Replace the `API_KEY` in the `script.js` file with your own API key.

```javascript
const API_KEY = "your_api_key_here";
```
## Acknowledgments

- [News API](https://newsapi.org/) for providing the news data.
- Icons from [FontAwesome](https://fontawesome.com/).
- Fonts from [Google Fonts](https://fonts.google.com/).
