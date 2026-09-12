# Country Phone Number Code Converter

A simple, interactive web tool that identifies a country based on its international phone number prefix. Enter the first few digits of any phone number in international format and instantly discover which country it belongs to.

## 🚀 Live Demo

Check out the live demo: [https://www.xn--msiu-goa8b.vn/github/country-phone-number-code-converter](https://www.xn--msiu-goa8b.vn/github/country-phone-number-code-converter)

## ✨ Features

- **Phone Prefix Lookup** – Enter the first 2 to 4 digits of an international phone number to identify the country
- **Real-Time Results** – See the country name appear automatically as you type or delete digits
- **International Format Support** – Works with numbers starting with `+` (e.g., `+84` for Vietnam)
- **`00` Prefix Handling** – Automatically converts the international `00` prefix to `+`
- **Comprehensive Coverage** – Supports phone codes for countries and territories worldwide
- **Clean Interface** – Simple, user-friendly design with a clear layout
- **Responsive** – Works on desktop, tablet, and mobile devices

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- JSON (country phone code data)

## 📁 Project Structure

```
country-phone-number-code-converter/
├── index.html                        # Main HTML file
├── style.css                         # Stylesheet
├── script.js                         # JavaScript logic for phone code lookup
├── data.json                         # Country phone code data
└── README.md                         # Project documentation
```

## 🔧 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/lemasieu/country-phone-number-code-converter.git
   ```
2. **Navigate to the project folder**
   ```bash
   cd country-phone-number-code-converter
   ```
   
3. **Run the application with a local server**

⚠️ Important: This project loads data from a JSON file, so you need to use a local development server instead of opening `index.html` directly in your browser to avoid CORS issues.

- **Using VS Code** – Install the "Live Server" extension, right-click on `index.html`, and select "Open with Live Server"
- **Using Python** – Run `python -m http.server` (Python 3) or `python -m SimpleHTTPServer` (Python 2) and open `http://localhost:8000`
- **Using Node.js** – Install `http-server` globally (`npm install -g http-server`) and run `http-server` in the project folder

## 📝 How It Works

1. **Enter a phone prefix** – Type the first 4 digits of an international phone number into the input field (e.g., `+84` for Vietnam)
2. **Delete digits from the right** – Remove the last digit one by one until a country name appears in the result field
3. **View the country** – The corresponding country name is displayed instantly
4. **Handle `00` prefix** – If the number starts with `00`, replace it with `+` before entering it

### Important Notes:

- Enter the first 4 digits of the phone number, then delete the rightmost digits one by one until the result appears
- If the phone number starts with `00`, replace it with `+` (e.g., `0084` → `+84`)
- The tool identifies the country associated with the phone code, which may not always reflect the user's current location

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request or open an Issue.
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open-source and available under the MIT License.
