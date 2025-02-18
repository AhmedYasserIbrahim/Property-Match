# Property Match

## Overview
This project is a web-based application that provides personalized property listings to users based on their preferences. Users can interact with property suggestions by liking or disliking them. If they dislike a property, they are prompted to provide predefined reasons for review. The collected feedback does not dynamically alter the suggestions but helps in understanding customer behavior.

## Features
- **Personalized Property Suggestions:** Generates suggestions for users based on stored preferences.
- **User-Specific Access:** Users access the application via a URL containing their phone number as a parameter.
- **Interactive Property Cards:** Users can like or dislike a property.
  - If disliked, user is prompted to enter the reason.
  - The selected reasons are collected for review purposes.
- **Smooth Transition Between Properties:** After interaction, the application transitions to the next property.

## Setup and Installation

### Prerequisites
- Install **Node.js** (if required for running the backend).
- A local or cloud-based web server (if necessary for hosting).
- A browser (Chrome, Firefox, Edge, etc.).

### Steps to Run Locally
1. **Clone the Repository**
   ```sh
   git clone --branch main --single-branch https://github.com/AhmedYasserIbrahim/Property-Match.git
   cd Property-Match

   ```
2. **Install Dependencies** (if applicable)
   ```sh
   npm install
   ```
3. **Run the Application**
   ```sh
   npm start
   ```
4. **Access the Application**
   - Open a browser and navigate to:
     ```
     http://localhost:3000
     ```
   - Enter the phone number to search

## Project Structure
```
property-listing-suggestions/
│── public/                # Static assets (HTML, CSS, images, etc.)
│── src/                   # Source code
│   ├── data/              # User preferences and property data
│   ├── components/        # UI components (property cards, buttons, etc.)
│   ├── services/          # Business logic (data fetching, filtering properties)
│   ├── app.js            # Main application logic
│── server.js              # Backend server (if applicable)
│── package.json           # Project dependencies and scripts
│── README.md              # Documentation
```

## Dependencies
- **Frontend:** JavaScript (HTML, CSS, JS)
- **Backend (if applicable):** Node.js, Express.js
- **Data Handling:** JSON or a simple database (if needed)

## Usage
1. Open the application using a URL with a phone number parameter.
2. View personalized property suggestions based on preferences.
3. Like or dislike properties.
4. If disliked, select reasons for disliking the property.
5. Continue browsing through properties.

## License
This project is open-source and available under the **MIT License**. Owned by Own.SA company.
