📚 Safe Route Finder Using Flask and GPT-4o

This project is a Flask web application that helps pedestrians find the safest route between two locations in New York City by analyzing historical crime data. The application uses Google Maps API to generate route suggestions and leverages OpenAI's GPT-4o to assess the safety of the routes.

🎯 Project Overview
✅ Provides safer route suggestions for pedestrians based on time of day.
✅ Analyzes potential dangers using NYC incident data from wow.csv.
✅ Integrates with Google Maps to generate route links.
✅ Uses GPT-4o to refine route suggestions and provide safer alternatives.
✅ Option to disable API usage to prevent unnecessary API credit usage.
📂 Project Structure

/safe-route-finder
├── /static
│   ├── /css
│   │   └── styles.css         # Styling for UI
│   └── /images
│       └── new-york-city-map.jpg  # Background map image
├── /templates
│   └── index.html             # Main HTML page
├── wow.csv                    # CSV file with NYC incident data
└── main.py                     # Main Flask application
└── README.md                   # Project documentation
⚙️ Prerequisites

Make sure you have the following installed:

Python (>= 3.8)
Flask (pip install Flask)
OpenAI Python Library (pip install openai)
Pandas (pip install pandas)
Python-dotenv (pip install python-dotenv)


--Project done by Abhishek Kumar, Sanika Mhadgut and Ankit Chaurasia--
