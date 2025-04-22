# Bankist App

**Bankist** is a sleek, interactive banking web application built with modern JavaScript (ES6+), HTML5, and CSS3. Designed as a learning project, Bankist showcases best practices in UI design, data formatting, and user experience, drawing inspiration from Jonas Schmedtmann’s renowned JavaScript course.

---

## 🚀 Live Demo

> **[View the Live Demo on GitHub Pages](https://your-username.github.io/bankist/)**

![Bankist Demo](./demo.gif)

---

## ✨ Key Features

- **Secure Authentication**: User login with PIN-based verification and auto-logout timer for enhanced security.
- **Real-Time Transaction Display**: View deposits and withdrawals with dynamically formatted dates (`Today`, `Yesterday`, or locale-specific) and currency values.
- **Account Balance & Summary**: Instantly calculates and presents current balance, total income, total expenses, and interest accrued.
- **Funds Transfer**: Seamless money transfers between accounts, with validations to ensure sufficient balance and prevent self-transfers.
- **Loan Requests**: Request loans based on transaction history; loans are granted if at least one deposit meets 10% of the requested amount.
- **Account Closure**: Easily close your account by confirming credentials; all user data is removed locally.
- **Transaction Sorting**: Toggle sorting of transaction history for quick analysis.

---

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/bankist.git
   cd bankist
   ```
2. **Open the application**
   - No build tools or server required.
   - Open `index.html` in your preferred web browser.

---

## 📋 Usage

1. **Login**
   - Use one of the demo accounts:
     | Username | PIN  | Owner               |
     | -------- | ---- | ------------------- |
     | `js`     | 1111 | Jonas Schmedtmann   |
     | `jd`     | 2222 | Jessica Davis       |

2. **Navigate the Dashboard**
   - **Balance**: Displays your up-to-date account balance.
   - **Movements**: Lists all transactions; green badges indicate deposits, red for withdrawals.
   - **Summary**: Shows totals for incoming funds, outgoing funds, and interest earned.

3. **Perform Operations**
   - **Transfer Funds**: Enter recipient’s username and amount, then click ➔.
   - **Request Loan**: Input desired loan amount; click ➔ to apply.
   - **Close Account**: Provide username and PIN; click ➔ to delete account.
   - **Sort Transactions**: Click the “SORT” button to reorder transactions.

---

## 📂 Project Structure

```
└── bankist/
    ├── index.html      # Main HTML file
    ├── style.css       # CSS styling
    ├── script.js       # Application logic
    └── README.md       # Project documentation
```

---

## 🛠️ Technologies & Tools

- **JavaScript (ES6+)**: Core application logic
- **HTML5 & CSS3**: Responsive and modern UI
- **Intl API**: Locale-aware date and currency formatting
- **Git & GitHub**: Version control and hosting

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Please follow these steps:
1. Fork the repository
2. Create a new branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*Built with ❤️ by Abdinasir Abuukar Mohamed*

