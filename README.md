# Interactive Budget Dashboard
An intuitive, single-file, and fully client-side personal budget dashboard to help you manage your finances effectively. This application is built with vanilla JavaScript, Chart.js, and Tailwind CSS, and it runs entirely in your browser with no backend required.

# ✨ Features
- Zero-Backend: Runs entirely in the browser. No need for servers, databases, or installations.

- Data Persistence: Your budget data is automatically saved to your browser's localStorage, so your information is there when you return.

- Interactive Charts: Visualize your finances with three dynamic charts powered by Chart.js:

- Budget vs. Actual: A bar chart comparing your budgeted amounts against your actual spending across major categories.

- Income Summary: A doughnut chart breaking down your actual income by source.

- Actual Breakdown: A doughnut chart showing the proportion of your actual spending on bills, expenses, savings, and debt.

- Fully Editable: All categories and financial entries can be edited in-place. Click on any value or category name to update it.

- Dynamic Tables: Add or remove items from Income, Bills, Expenses, Savings, and Debt categories on the fly.

- Real-time Calculations: Totals and summaries update instantly as you make changes.

# Key Financial Insights:

- Left to Budget: See exactly how much of your income is unallocated.

- Days Left: A countdown for your current budget period.

- Customizable Overview: Set your name, budget period (start/end dates), and preferred currency.

- Reset to Default: A reset button is available to clear your data and start over with the default template.

- Responsive Design: The dashboard is fully responsive and works beautifully on desktops, tablets, and mobile devices.

# 🛠️ Tech Stack
- HTML5: For the basic structure and content.

- Tailwind CSS: For a utility-first approach to styling and creating a modern, responsive UI.

- Vanilla JavaScript (ES6+): For all the logic, calculations, and DOM manipulation.

- Chart.js: For creating beautiful and interactive charts.

# 🚀 How to Run the Project
This project is designed for simplicity and requires no local server, build steps, or dependencies.

Simply open the index.html file directly in your web browser.

You can do this in a few ways:

- Double-click the index.html file in your file explorer.

- Right-click the file and choose "Open with" your preferred browser (e.g., Chrome, Firefox, Safari).

- Drag and drop the index.html file into an open browser window.

- Once opened, the dashboard will be fully functional.

# 📝 How to Use
1. Download: Get the index.html file from the repository.

2. Open: Open the file in your browser as described in the "How to Run" section.

3. Start Budgeting: That's it! The dashboard is ready to use.

All your data will be saved in your browser's localStorage. As long as you use the same browser and don't clear your site data, your budget will be waiting for you.

# 🔧 How It Works
This project is intentionally simple and self-contained in a single index.html file.

- Styling: Tailwind CSS is included via a CDN link in the <head>. Custom styles are added within a <style> tag for more specific tweaks.

- Logic: All the JavaScript code is contained within a <script> tag at the bottom of the body. It handles:

- Loading data from localStorage or initializing with a default template.

-- Saving any changes back to localStorage.

-- Rendering and updating the tables and charts.

-- Handling all user interactions and calculations in real-time.

-- Data Structure: The budget data is stored in a single JavaScript object which has arrays for income, bills, expenses, savings, and debt.

# ✏️ Customization
You can easily customize the default budget template by modifying the defaultBudgetData object within the main <script> tag in the index.html file.

// --- INITIAL DATA (Default template) ---

const defaultBudgetData = {
    
    income: [
        { category: 'Salary', budget: 650000, actual: 650000 },
        // ... add or change income sources
    ],
    bills: [
        { category: 'Rent', due: '1st', budget: 180000, actual: 180000 },
        // ... add or change bills
    ],
    // ... and so on for expenses, savings, and debt
};

# 👤 Author
Fahed Ahmad

Email: fahedahmad2002@gmail.com

LinkedIn: https://www.linkedin.com/in/fahed-ahmad

# 📄 License
This project is open-source and available under the MIT License.

