# 🌍 Power Apps Travel Advisor Powered by Google Gemini

Welcome to the repository for the Power Apps Travel Advisor application, an innovative solution leveraging Google Gemini's capabilities to enhance travel planning experiences. This app uses Gemini's multimodal vision endpoint for location identification from images and the text generation endpoint to create detailed itineraries. Here's how you can use this application to transform travel planning into a seamless, AI-powered process.


https://github.com/PriyaranjanKS/PowerPlatform_AITravelAdvisor/assets/29351010/b5826f08-437c-4a28-9936-68202412b210


## 🚀 Features

- **Location Identification**: Upload an image to identify famous landmarks or locations using Google Gemini's vision capabilities.
- **Dynamic Itinerary Generation**: Automatically generate a 3-day or 5-day travel itinerary based on the identified location.
- **HTML Itinerary Display**: View the generated itinerary in a beautifully formatted HTML output suitable for Power Apps.

## 📋 Prerequisites

Before you begin, ensure you have:

- A Microsoft Power Platform environment with access to Power Apps and Power Automate.
- A Google AI Studio account with access to Google Gemini and an API key generated for use.

## 🔑 Google Gemini API Key

To use this solution, you'll need an API key from Google AI Studio, specifically for Gemini services. Make sure to generate this key before importing the solution into Power Platform.

## 📥 How to Import the Solution

1. **Download the Solution Package**: Clone this repository or download the solution package provided in the releases section.
2. **Import into Power Platform**:
   - Navigate to your Power Platform environment.
   - Go to **Solutions** and choose **Import**.
   - Upload the downloaded solution package and follow the on-screen instructions to complete the import.
3. **Configure API Key**:
   - Upon import, you will be prompted to enter your Google Gemini API key.
   - Input your key to enable the application to communicate with Google Gemini services.

## 💡 Usage Instructions

### Identifying a Location

- Use the **Add Picture** control to upload an image of the place you're interested in.
- Click the **Find** button to identify the location. The identified location will be displayed in a text label within the app.

### Generating an Itinerary

- Once the location is identified, choose between a 3-day or 5-day itinerary.
- Click the corresponding button to generate the itinerary. The itinerary will be displayed in an HTML control, formatted for easy reading.

## 🌟 Highlighted Features

- **Image Location Locator**: This Power Automate flow processes the image upload and utilizes Google Gemini to identify the location.
- **Itenary Generator**: After location identification, this module generates a detailed travel itinerary using Google Gemini.

## 📘 Documentation

For more detailed instructions on setting up and using Google Gemini within your applications, refer to the [Google AI Studio documentation](https://aistudio.google.com/gemini).

## 🤝 Contributing

Your contributions are welcome! If you have suggestions for improving this application or want to contribute to its development, please feel free to fork the repository, make changes, and submit a pull request.

## 📄 License

This project is licensed under the MIT License .

## ✉️ Support

If you encounter any issues or have questions about deploying this solution, please open an issue in this repository.

---

Transform your travel planning experience with our Power Apps Travel Advisor, powered by the innovative AI capabilities of Google Gemini.
