
Built by https://www.blackbox.ai

---

# faddedsmm - SMM Panel Frontend

## Project Overview
faddedsmm is a sleek and responsive frontend application for a social media marketing (SMM) panel. Built using React and Tailwind CSS, it provides users with an intuitive interface to manage their social media marketing efforts efficiently. The application features a wallet management system, services selection, and easy navigation for a seamless user experience.

## Installation
To get started with faddedsmm, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/faddedsmm.git
   cd faddedsmm
   ```

2. **Install dependencies**:
   Make sure you have Node.js and npm installed. Then run:
   ```bash
   npm install
   ```

3. **Run the development server**:
   ```bash
   npm run dev
   ```
   Visit `http://localhost:3000` in your browser.

## Usage
Once the application is running, you can navigate through various functionalities available in the panel:
- **Wallet Management**: Check your wallet balance and add funds.
- **Service Selection**: Explore different services available for marketing.
- **Order Management**: Create new orders and manage existing ones.

### Navigation
Use the bottom navigation bar for quick access to main functionalities:
- Dashboard
- Wallet
- Service List
- Chat
- User Profile

## Features
- **Responsive Design**: Optimized for both mobile and desktop views.
- **Wallet Management**: View wallet balances and funding options.
- **Service Listings**: Access various social media marketing services.
- **Easy Navigation**: Intuitive navigation through the application.
- **User Profile Management**: Manage user profile details.

## Dependencies
The project uses several dependencies for various functionalities. Below are the key dependencies listed in the `package.json`:

- **Frontend Libraries**:
  - `@heroicons/react`: ^2.0.18
  - `axios`: ^1.4.0
  - `next`: ^13.4.7
  - `react`: ^18.2.0
  - `react-dom`: ^18.2.0
  - `react-query`: ^3.39.3
  - `zustand`: ^4.3.8

- **Dev Dependencies**:
  - `@types/node`: ^20.17.32
  - `@types/react`: ^18.3.20
  - `@types/react-dom`: ^19.1.3
  - `autoprefixer`: ^10.4.14
  - `postcss`: ^8.4.24
  - `tailwindcss`: ^3.3.2
  - `typescript`: ^5.1.3

## Project Structure
The project structure is organized as follows:

```
faddedsmm/
├── node_modules/            # npm packages
├── public/                  # static files
├── src/
│   ├── components/          # React components
│   ├── pages/               # Next.js pages
│   ├── styles/              # CSS stylesheets (Tailwind CSS)
│   ├── utils/               # Utility functions
│   └── types/               # TypeScript types
├── .gitignore                # files to ignore in git
├── package.json              # npm package configuration
├── package-lock.json         # npm package lock file
├── postcss.config.js         # PostCSS configuration
├── tsconfig.json             # TypeScript configuration
└── tailwind.config.js        # Tailwind CSS configuration
```

## Contributing
Contributions are welcome! Please create a pull request or open an issue if you find any bugs or if you have suggestions for new features.

## License
This project is open source and available under the [MIT License](LICENSE).