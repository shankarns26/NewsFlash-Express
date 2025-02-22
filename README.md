# Daily News Application

A modern, responsive web application that provides real-time news updates across various categories using the NewsAPI service.

## Features

- **Real-time News Updates**: Get the latest news from reliable sources
- **Category-based News**: Browse news by categories including:
  - Technology
  - Business
  - Entertainment
  - Sports
  - Health
- **Search Functionality**: Search for specific news articles using keywords
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Clean User Interface**: Modern and intuitive UI built with Bootstrap

## Technology Stack

- **Backend**: Python Flask
- **Frontend**: HTML5, CSS3, JavaScript
- **UI Framework**: Bootstrap 5
- **News Data**: NewsAPI
- **Template Engine**: Jinja2

## Benefits

1. **Stay Informed**: Get instant access to the latest news across multiple categories
2. **User-Friendly**: Clean and intuitive interface makes navigation effortless
3. **Mobile-First**: Responsive design ensures great experience on all devices
4. **Fast Loading**: Optimized performance for quick news access
5. **Reliable Sources**: News from trusted sources via NewsAPI

## Installation

1. Clone the repository
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your NewsAPI key (get one from [NewsAPI](https://newsapi.org/))
4. Run the application:
   ```bash
   python app.py
   ```

## Usage

1. **Browse Categories**: Navigate through different news categories using the cards on the homepage
2. **Search News**: Use the search bar in the navigation to find specific news articles
3. **Read Articles**: Click "Read More" on any news card to view the full article on the source website

## Application Structure

- `app.py`: Main Flask application file containing routes and news fetching logic
- `templates/`: Contains HTML templates
  - `index.html`: Homepage template
  - `search.html`: Search results template
- `static/`: Static files (CSS, JavaScript)
- `requirements.txt`: Python dependencies

## Development

The application is built with maintainability and scalability in mind. The code is organized following Flask best practices, with separate concerns for routing, templating, and static assets.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
