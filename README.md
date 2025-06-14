🛒 Shopping Cart [Live](https://shopping-cart-zh9s.onrender.com)

A simple shopping cart web application built using React.
It allows users to browse items, add/remove products from the cart, and view the total price dynamically.


🚀 Features

📦 Add items to the cart
➖ Remove items from the cart
🔄 Update item quantities
💰 Real-time calculation of total price
⚡ Clean and responsive user interface


🛠 Technologies Used

React
JavaScript (ES6+)
Tailwind CSS
Node.js (for build & tooling)

📂 Project Structure
/src
 ├── components/      # Reusable components (e.g. Cart, ProductList)
 ├── pages/           # (If used) App pages/views
 ├── App.js           # Main app component
 ├── index.js         # Entry point
/public
 └── index.html
 
📦 Installation
bash

# Clone the repository
git clone https://github.com/Shrishti-27G/Shopping-Cart.git
cd Shopping-Cart

# Install dependencies
npm install

🏗️ Run Locally
bash
npm start
Visit: http://localhost:3000

🏭 Build for Production
bash
npm run build


⚠️ Notes
The app was bootstrapped with Create React App (CRA).
Consider migrating to Vite or Next.js in the future as CRA is no longer maintained.
If you encounter the Babel plugin warning, install:

bash

npm install --save-dev @babel/plugin-proposal-private-property-in-object
