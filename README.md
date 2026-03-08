MediAccess - Modern Healthcare Platform 🏥
MediAccess is a responsive frontend web application designed to streamline access to critical healthcare services. It allows users to check real-time hospital bed availability, explore vaccination centers, compare emergency fees, find top doctors, and interact with an AI-powered symptom-checking chatbot.

✨ Features
Hospital Bed Availability: Check real-time ward and ICU bed capacity across various hospitals. Filter results by city and hospital type (Government/Private).

Vaccination Centers: Locate nearby vaccination hubs, view available vaccines (Covishield, Covaxin, etc.), and check operating schedules.

Emergency Fees: Transparently compare emergency entry fees, consultation costs, and average ICU per-day costs across different hospitals.

Doctor Directory: Browse and filter highly-rated medical specialists by their fields (Cardiology, Neurology, Pediatrics, etc.).

MediBot AI (Health Assistant): An integrated chatbot that analyzes user symptoms, predicts potential conditions, assesses severity, and recommends the appropriate medical specialist.

Global Search: Quickly search for hospitals, cities, or specific medical services.

Responsive Design: A modern, accessible UI built with CSS variables and flexbox/grid layouts.

🛠️ Tech Stack
This project is built using vanilla web technologies, requiring no complex build tools or frameworks:

HTML5: Semantic structuring and single-page application (SPA) simulation using hash routing.

CSS3: Custom styling, variables, responsive design, and CSS animations.

JavaScript (ES6+): DOM manipulation, state management, search/filter logic, and chatbot symptom analysis.

FontAwesome: For rich, scalable vector icons.

📂 File Structure
index.html: The main entry point containing the UI structure, navigation, and page sections.

styles.css: All styling rules, CSS variables, and chatbot animations.

app.js: Core logic for routing, rendering dynamic content, filtering, and global search.

data.js: Mock database containing extensive, curated arrays of hospitals, doctors, and vaccination centers.

chatbot.js: The logic for MediBot AI, including the disease database, symptom matching algorithm, and chat state management.

🚀 Getting Started
Since this is a vanilla frontend project, setup is completely frictionless.

Download/Clone the repository containing the 5 files (index.html, styles.css, app.js, chatbot.js, data.js).

Ensure all files are in the same directory.

Open index.html in any modern web browser (Chrome, Firefox, Safari, Edge).

No local server, Node.js, or npm installation is required.

💡 How to Use
Navigate: Use the top navigation bar to switch between Home, Bed Availability, Vaccines, Emergency Fees, and Doctors.

Filter & Search: Use the dropdowns on the "Beds" and "Doctors" pages to narrow down your results. Use the search bar on the home page for quick lookups.

View Details: Click "View Details" on any hospital card to see a detailed breakdown of its services, specific bed counts, and affiliated doctors.

Use MediBot: Click the floating "MediBot AI" tab in the bottom right corner. Type in your symptoms (e.g., "I have a severe headache and blurred vision"), rate your severity, and let the bot suggest the best medical approach and specific doctors from the database.

📝 Future Enhancements (Roadmap)
Integrate a backend API for live hospital data fetching.

Add a functional appointment booking system.

Implement user authentication for personalized health dashboards.

Expand the MediBot symptom database using NLP libraries.

Created for the MediAccess platform.
