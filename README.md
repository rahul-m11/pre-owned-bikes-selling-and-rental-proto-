Bike Hub - Second-Hand Bike Marketplace
Project Overview
Bike Hub is a mobile-first web application designed as a dedicated marketplace for buying and selling second-hand motorcycles. It provides a user-friendly platform for individual sellers and professional organisers (brokers) to list bikes for sale. Buyers can easily browse, search, and connect with sellers. The application is built entirely within a single HTML file using React (loaded via CDN) and styled directly with JavaScript objects, simulating a modern mobile app experience.

Key Features
User Authentication: A simple and clean login screen to get users into the app.
⦁	Dynamic Home Screen: Displays various categories of bikes (Cruisers, Sport Bikes, Commuters) in horizontally scrollable sections.
⦁	Verified Organisers: A special section for professional, trusted sellers (brokers) with dedicated profile pages showing all their available bikes.
⦁	Top Sellers Leaderboard: A competitive leaderboard screen showcasing the most successful sellers on the platform, ranked by sales.
⦁	Sell Your Bike Flow: An intuitive, multi-step process for users to list their own bikes for sale, including category selection, photo upload, and details entry.
⦁	Detailed Listings: Each bike has a detail page with a larger image, price, specifications (year, KMs driven), and a full description.
⦁	Shortlist Functionality: Allows users to save bikes they are interested in for later viewing.
⦁	AI-Powered Assistant: A text-based chatbot (BikeBot) that can answer user questions about bike maintenance, buying tips, and selling advice.

Note: As this is a prototype, the AI functionality is present in the code but requires an API key to be fully activated. See the "Activating the AI Assistant" section below.

Responsive Mobile-First Design: The entire interface is designed to look and feel like a native mobile application.
How to Run the Project
This project is self-contained in a single index.html file and does not require a complex setup. The easiest way to run it is with the Live Server extension in Visual Studio Code.
Prerequisites
Visual Studio Code

Step-by-Step Instructions
⦁	Save the Code: Save the entire code from the bike_hub_app_v3 document into a file named index.html on your computer.
⦁	Install Live Server in VS Code:
⦁	Open VS Code.
⦁	Go to the Extensions view (click the icon with four squares on the sidebar).
⦁	Search for Live Server by Ritwick Dey.
⦁	Click Install.
⦁	Launch the Application:
⦁	Open the index.html file in VS Code.
⦁	Right-click anywhere inside the code editor.
⦁	Select "Open with Live Server" from the menu.

Your default web browser will open with the application running. The page will automatically refresh every time you save changes to the file.

Technology Stack
Frontend: React.js (via CDN)
Markup/Styling: HTML5, CSS-in-JS (styles are managed as JavaScript objects within the code)
Transpiler: Babel (loaded via CDN to transpile JSX in the browser)
AI Integration: Google Gemini API (for the AI Bike Assistant)

Activating the AI Assistant (Optional)
The AI chatbot feature is built into the app but is not active by default because it requires a personal API key from Google.
To enable the AI assistant:
⦁	Get a Gemini API Key:
⦁	Visit Google AI Studio.
⦁	Sign in with your Google account and follow the steps to create a new API key.
⦁	Add the Key to the Code:
⦁	Open the index.html file.
⦁	Find the ChatbotScreen component in the code.
⦁	Inside this component, locate the getApiResponse function.
⦁	You will see a line: const apiKey = "";

Paste your generated API key between the quotation marks, like this: const apiKey = "YOUR_API_KEY_HERE";

Save and Reload: Save the file. Live Server will automatically reload the app in your browser, and the AI chatbot will now be fully functional.

⚠️ Disclaimer
Please note that all data used for listing bike details, organisers, and the seller leaderboard in this project is 100% mock data for demonstration purposes only.
