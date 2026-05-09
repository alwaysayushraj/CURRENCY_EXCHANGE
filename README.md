💱 Currency Exchange
A responsive and dynamic web application that provides real-time currency exchange rates. Users can input an amount and convert it between various global currencies instantly.

🚀 Key Features
Real-Time Data: Fetches the latest exchange rates using the Currency API.

Dynamic UI: Automatically updates country flags when a new currency is selected.

Comprehensive Coverage: Includes an extensive list of global currencies mapped to their respective country codes.

Responsive Design: Styled with CSS Flexbox for a clean look across different screen sizes.

🛠️ Built With
HTML5: Semantic structure for the converter interface.

CSS3: Custom styling, including Google Fonts and FontAwesome icons.

JavaScript (ES6+): * Asynchronous Programming: Uses fetch and async/await for API calls.

DOM Manipulation: Dynamically populates dropdowns and updates the UI.

📸 Preview
<img width="1366" height="768" alt="Screenshot" src="https://github.com/user-attachments/assets/79464d2f-8db8-4694-9810-cbc9e3791e74" />

💡 How It Works
Data Mapping: The code.js file contains a countryList object that maps currency codes (e.g., USD) to country codes (e.g., US) for flag rendering.

Initialization: On page load, the script populates the dropdowns and fetches the initial exchange rate for USD to INR.

API Integration: When "Get Exchange Rate" is clicked, the app sends a request to:
https://latest.currency-api.pages.dev/v1/currencies/{fromCurr}.json

Calculations: The app parses the JSON response, identifies the rate for the target currency, and multiplies it by the user's input.
