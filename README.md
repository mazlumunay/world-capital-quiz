# World Capital Quiz 🌍

A fun and interactive web application to test your knowledge of world capitals! Built with Node.js, Express, and EJS.

## Features

- Interactive quiz interface
- Real-time score tracking
- Random question generation
- Clean and responsive design
- Simple and intuitive user experience

## Screenshots

The application displays random countries and asks you to guess their capitals!

## Technologies Used

- **Node.js** - Runtime environment
- **Express.js** - Web application framework
- **EJS** - Template engine for dynamic HTML
- **Body-Parser** - Middleware for parsing request bodies
- **PostgreSQL (pg)** - Database support
- **Axios** - HTTP client

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/world-capital-quiz.git
cd world-capital-quiz
```

2. Install dependencies:
```bash
npm install
```

3. Start the application:
```bash
node index.js
```

4. Open your browser and navigate to:
```
http://localhost:3000
```

## How to Play

1. Launch the application
2. You'll be presented with a country name
3. Type in the capital city
4. Submit your answer
5. See if you're correct and view your score
6. Continue playing to improve your score!

## Project Structure

```
world-capital-quiz/
├── public/
│   ├── images/      # Image assets
│   └── styles/      # CSS stylesheets
├── views/
│   └── index.ejs    # Main template
├── capitals.csv     # Capital cities data
├── index.js         # Main application file
├── solution.js      # Alternative implementation
├── package.json     # Project dependencies
└── README.md        # Project documentation
```

## Dependencies

```json
{
  "axios": "^1.4.0",
  "body-parser": "^1.20.2",
  "ejs": "^3.1.9",
  "express": "^4.18.2",
  "pg": "^8.11.3"
}
```

## Configuration

The application runs on port 3000 by default. You can modify this in the `index.js` file:

```javascript
const port = 3000;
```

## Future Enhancements

- [ ] Add more countries and capitals
- [ ] Implement difficulty levels
- [ ] Add timer functionality
- [ ] Create leaderboard system
- [ ] Add hints feature
- [ ] Support for multiple languages

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgments

- Inspired by geography education apps
- Built as a learning project for Node.js and Express
- Thanks to all contributors!

---

⭐ Star this repository if you found it helpful!