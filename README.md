Movie Recommendation using Machine Learning

Objective
To recommend movies based on user emotions or genres by fetching titles from IMDb using web scraping techniques.

Methodology
Mapping Emotions to URLs: A predefined dictionary links emotions (Drama, Action, etc.) to IMDb genre pages.

Web Scraping:

HTTP Requests: Fetches data from IMDb using the requests library.
HTML Parsing: Extracts movie titles using BeautifulSoup and regex patterns.

User Interaction:
Prompts the user to input an emotion.
Displays a curated list of movies based on the selected genre.

Key Features
Dynamic fetching of movie titles from IMDb.
Simple regex-based filtering for accuracy.
Ensures a user-friendly limit on the number of displayed titles.
