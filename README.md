# BharatGaav Connect 🇮🇳

A web platform connecting rural service providers with people seeking essential services across villages in India.

## Features

- 📱 **Easy Registration**: Simple form to register services
- 🔍 **Quick Search**: Filter services by type, name, or location
- 📍 **Location-Based**: Search services by state, district, and village
- 💾 **Persistent Storage**: Services saved in browser's local storage
- 📞 **Direct Contact**: One-click calling feature
- 🎨 **Responsive Design**: Works on desktop, tablet, and mobile devices

## Service Categories

- Doctor/Medical
- Mechanic
- Electrician
- Plumber
- Teacher
- General Shop
- Farmer/Agriculture
- Other

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs entirely in the browser

### Installation

1. Clone the repository:
```bash
git clone https://github.com/shivamshuklaa06-ai/APNA-GAAV.git
```

2. Navigate to the project directory:
```bash
cd APNA-GAAV
```

3. Open `index.html` in your web browser or serve it with a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (npm)
npx http-server

# Using Node.js (yarn)
yarn global add http-server
http-server
```

4. Visit `http://localhost:8000` in your browser

## File Structure

```
APNA-GAAV/
├── index.html       # Main HTML file
├── styles.css       # Styling
├── script.js        # JavaScript functionality
└── README.md        # Documentation
```

## How to Use

### Register a Service
1. Navigate to "Add Service" section
2. Fill in your details:
   - Full Name
   - Service Type
   - Phone Number
   - State
   - District
   - Village
3. Click "Register Service"

### Search Services
1. Go to "Available Services" section
2. Use the search bar to find by name, service type, or location
3. Use the dropdown to filter by service type
4. Click the phone number to call directly

### Delete a Service
1. Click the "Delete" button on any service card
2. Confirm the deletion

## Data Storage

All data is stored locally in your browser using `localStorage`. Data persists across browser sessions but is cleared if you clear your browser cache.

## Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling and responsive design
- **JavaScript (Vanilla)** - Functionality
- **LocalStorage API** - Data persistence

## Future Enhancements

- [ ] Backend database integration
- [ ] User authentication
- [ ] Ratings and reviews
- [ ] Service verification system
- [ ] Multi-language support
- [ ] Mobile app version
- [ ] Maps integration
- [ ] Email notifications

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the MIT License.

## Contact

For questions or suggestions, please reach out through:
- GitHub Issues: [APNA-GAAV Issues](https://github.com/shivamshuklaa06-ai/APNA-GAAV/issues)
- GitHub Profile: [@shivamshuklaa06-ai](https://github.com/shivamshuklaa06-ai)

## Support

If you find this project helpful, please consider:
- ⭐ Starring the repository
- 🐛 Reporting bugs through GitHub Issues
- 💡 Suggesting new features
- 📢 Sharing the project with others

---

**Made with ❤️ for Rural India**