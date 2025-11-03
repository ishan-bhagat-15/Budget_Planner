# Budget_Planner
A simple Personal Budget Planner built with HTML, CSS, and JavaScript. Users can add income and expenses, and the app automatically calculates total expenses and remaining balance. Fully frontend-based, modular code structure, and supports Docker deployment.
This is a simple and efficient Personal Budget Planner web application built using HTML, CSS, and JavaScript (ES Modules). The project allows users to manage their monthly income, add expenses with descriptions, and automatically calculates the total expenses and remaining balance. It is designed to help users easily track and visualize their spending habits.

The application follows a modular JavaScript architecture with separate files handling core functionalities:

storageService.js: Stores and manages income and expense data

budgetService.js: Calculates total expenses and balance

uiService.js: Updates values and renders expense items on the screen

main.js: Connects UI with business logic using event handling

This separation of logic makes the project clean, scalable, and easier to maintain.

The project is completely frontend-based — no database, backend, or external API is used. All data is processed dynamically in the browser.

It also includes a Dockerfile, enabling users to run and deploy the application anywhere using Docker, ensuring portability and consistent behavior across systems.

🔧 Tech Used

HTML (Structure)

CSS (Styling + Responsive UI)

JavaScript ES Modules (Logic & Components)

Docker (Optional Deployment)

This project is ideal for beginners exploring modular JavaScript, DOM manipulation, and Docker-based deployment.
