# Realtime Currency Converter

A simple, user-friendly web application that converts currencies in real-time using live exchange rates.

## Features

- **Real-time Conversion**: Get up-to-date currency exchange rates
- **Multiple Currencies**: Support for 150+ currencies worldwide
- **Swap Currencies**: Quickly switch between "From" and "To" currencies with a single click
- **Input Validation**: Ensures only valid numeric inputs greater than 0
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **User-Friendly Interface**: Clean and intuitive UI with visual feedback

## Technologies Used

- **HTML5**: For the structure and layout
- **CSS3**: For styling and responsive design
- **JavaScript (ES6 Modules)**: For functionality and API integration
- **External API**: Fetches real-time exchange rates from a currency conversion API

## Project Structure

```
currency_converter/
├── index.html          # Main HTML file with UI structure
├── script.js           # Main JavaScript file with conversion logic
├── style.css           # CSS stylesheet for styling
├── currencyCodes.js    # Currency codes and API key configuration
├── README.md           # Project documentation
└── coinExchangeSticker.png  # Favicon/sticker image
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- An internet connection (required for live exchange rates)

### Installation

1. Clone or download this project to your local machine
2. Navigate to the project directory
3. Open `index.html` in your web browser

```bash
# Simply open the file in your browser
# No installation or build process required!
```

## How to Use

1. **Enter Amount**: Type the amount you want to convert in the input field
2. **Select Currencies**: 
   - Choose the currency you want to convert FROM (default: USD)
   - Choose the currency you want to convert TO (default: INR)
3. **Swap Currencies**: Click the swap button to quickly exchange the FROM and TO currencies
4. **Convert**: Click the "Convert" button to get the exchange rate and converted amount
5. **View Result**: The converted amount and exchange rate will be displayed below

## Features Explained

### Input Validation
- Accepts only numeric values greater than 0
- Displays an error message in red if invalid input is provided
- Visual feedback with red border on invalid input

### Currency Selection
- Dropdown menus display currency code and country name
- Easy to search and select from 150+ currencies
- Default currencies: USD (From) and INR (To)

### Currency Swap
- Click the swap button to instantly reverse the FROM and TO currencies
- Maintains the conversion amount while switching directions

## API Integration

This project uses a currency conversion API to fetch real-time exchange rates. The API key and endpoint are configured in `currencyCodes.js`.

## Error Handling

The application handles various error scenarios:
- **Invalid Input**: Shows error message for non-numeric or zero values
- **API Errors**: Displays status messages for network or API issues
- **Empty Fields**: Prevents conversion with empty input

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

- Add conversion history tracking
- Support for cryptocurrency conversion
- Multiple theme options

## License

This project is open source and available under the MIT License.

## Contributing

Contributions are welcome! Feel free to fork this project and submit pull requests with improvements.

## Support

If you encounter any issues or have suggestions, please open an issue on the project repository.

---

**Enjoy converting currencies with ease!** 💱
