
# 📊 Modabbir - Personal Finance Dashboard

> **Manage your money smarter, not harder.** A comprehensive, RTL-supported dashboard for tracking income, expenses, and savings in real-time.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

---

## 📖 Table of Contents
- [Project Description](#-project-description)
- [Features](#-features)
- [Demo](#-demo)
- [Installation](#-installation)
- [Usage](#-usage)
- [Technologies Used](#-technologies-used)
- [Contributing](#-contributing)
- [Roadmap](#-roadmap)
- [Credits](#-credits)
- [License](#-license)

---

## 📝 Project Description

**Modabbir** is a modern, responsive personal finance dashboard designed specifically for Arabic-speaking users with native Right-to-Left (RTL) support. It solves the problem of cluttered spreadsheets and complex accounting software by providing a clean, visual interface to track financial health.

Whether you are a freelancer wanting to track sporadic income or a household manager budgeting for monthly bills, Modabbir gives you a clear snapshot of where your money is going.

---

## ✨ Features

- **RTL-First Design**: Built from the ground up for Arabic language support.
- **Interactive Dashboard**:
    - **Summary Cards**: At-a-glance view of Current Balance, Income, and Expenses with percentage indicators.
    - **Visual Budget Tracking**: Progress bars showing budget utilization across categories (Entertainment, Bills, Shopping, etc.).
    - **Transaction History**: Detailed table view of recent transactions with status indicators.
- **Smart Visualizations**:
    - **Income vs. Expense Chart**: CSS-only bar charts to visualize weekly financial flow.
    - **Virtual Credit Card**: A realistic, 3D-flippable credit card component for managing payment methods.
- **Bill Management**: dedicated section for tracking upcoming monthly bills with due date alerts.
- **Responsive Layout**: Seamlessly adapts to desktop, tablet, and mobile screens using CSS Grid and Flexbox.

---

## 🚀 Installation

To run this project locally, you don't need any complex build tools or package managers.

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari).

### Steps
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/AhmadAbdalla-SE/Dashboard.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Dashboard
    ```
3.  **Open the project:**
    Simply open the `index.html` file in your browser.
    - On Windows: Double-click `index.html` or run `start index.html` in the command prompt.
    - On Mac: Run `open index.html`.
    - On Linux: Run `xdg-open index.html`.

---

## 💻 Usage

Once the dashboard is open in your browser, you can:

- **Navigate Sections**: Use the sidebar to switch between Dashboard, Transactions, Budgets, and Savings.
- **Add Transactions (Mock UI)**: Click on the "Add Money" or "Send Money" quick action buttons in the sidebar (frontend logic implementation pending).
- **View Card Details**: Hover over the virtual credit card to flip it and view the CVV/security code simulation.

Example of the project structure:
```
/
├── index.html          # Main HTML structure
├── styles/
│   ├── style.css       # Main stylesheet (Grid, Flexbox, Animations)
│   └── fontawesome/    # Icon library
└── images/             # Assets and icons
```

---

## 🛠 Technologies Used

- **Frontend**:
    - **HTML5**: Semantic markup for accessibility and SEO.
    - **CSS3**:
        - **CSS Grid & Flexbox**: For the complex, responsive layout.
        - **CSS Variables**: For consistent theming (colors, fonts).
        - **Animations**: Keyframe animations for the credit card flip and loading states.
    - **JavaScript**: (Currently minimalist/none, pure CSS implementation).
- **Icons**: FontAwesome 6.
- **Fonts**: 'Exo 2' and 'IBM Plex Sans Arabic' from Google Fonts.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## 🗺 Roadmap

- [ ] Add JavaScript logic for real-time data updates.
- [ ] Implement LocalStorage or a backend database (Firebase/Supabase) to save user data.
- [ ] Add Dark Mode toggle.
- [ ] Create a dedicated "Settings" page for profile management.

---

## 👏 Credits

- Icons by [FontAwesome](https://fontawesome.com).
- Fonts by [Google Fonts](https://fonts.google.com).

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
