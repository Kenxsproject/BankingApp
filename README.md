## Introduction
Welcome to My Banking App project! This project is designed to emulate various banking operations. Developed with a focus on security, responsiveness, and user experience, Horizon provides account management, transaction history, and the ability to add banks.


## How to Demo
* First navigate to this page https://banking-app-umber-tau.vercel.app/
* Go to sign up and create an account
  - Link a bank account using these credentials: User: user_good Password: pass_good
  - When directed to a mobile code press submit
## 💵Features
**Authentication**: An ultra-secure SSR authentication with proper validations and authorization

**Connect Banks**:Integrates with Plaid for multiple bank account linking

**Home Page**:Shows general overview of the user account with the total balance from all connected banks, recent transactions, money spent on different categories, etc

**My Banks**:Check the complete list of all connected banks with respective balances, account details

**Transaction History**: Includes pagination and filtering options for viewing transaction history of different banks

**Real-time Updates**:Reflects changes across all relevant pages upon connecting new bank accounts.

**Funds Transfer**:Allows users to transfer funds using Dwolla to other accounts with required fields and recipient bank ID.

**Responsiveness**:Ensures the application adapts seamlessly to various screen sizes and devices, providing a consistent user experience across desktop, tablet, and mobile platforms.

## 💳Tech Stack
* Shadcn
* Dwolla API
* Plaid API
* React
* Next.JS
* Tailwind CSS
* TypeScript
* ChartJS
* Zod
* Appwrite
