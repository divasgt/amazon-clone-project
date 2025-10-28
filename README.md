# 🛍️ Amazon.com E-commerce Frontend

This project is a simplified frontend implementation of an e-commerce website resembling Amazon. It allows users to browse products, add them to a cart, view their order history, track orders, and proceed through a checkout process. It showcases fundamental web development concepts and provides a foundation for building more complex e-commerce applications.

### 🔗 Live Link: https://divasgt.github.io/amazon-clone-project/

## 🚀 Key Features

*   **Product Browsing:** Displays a grid of products with images, names, ratings, and prices.
*   **Search Functionality:** Includes a search bar for users to find specific products.
*   **Shopping Cart:** Allows users to add products to a cart and view the cart contents.
*   **Order Management:** Enables users to view their order history and track the status of their orders.
*   **Checkout Process:** Guides users through a simplified checkout process, including order summary and payment summary.
*   **Dynamic Updates:** Utilizes JavaScript to dynamically update the cart quantity, product listings, and order information.
*   **Local Storage Persistence:** Persists cart data using local storage, allowing users to maintain their cart across sessions.

## 🛠️ Tech Stack

*   **Frontend:**
    *   HTML5
    *   CSS3
    *   JavaScript (ES6+)
*   **Styling:**
    *   Custom CSS (organized with shared and page-specific styles)
*   **Fonts:**
    *   Roboto (Google Fonts)
*   **Data Handling:**
    *   JSON (for product data)
    *   Local Storage (for cart persistence)
*   **JavaScript Libraries:**
    *   dayjs (for date manipulation)
*   **Other:**
    *   `XMLHttpRequest` and `fetch` API (for data loading)

## 📸 Screenshots

<img width="1675" height="974" alt="image" src="https://github.com/user-attachments/assets/704ad7c7-dc4f-4ec7-b1df-7a8e333786f9" />

<img width="1674" height="971" alt="image" src="https://github.com/user-attachments/assets/77a083b9-1522-45f3-a6b8-5738f13c49b7" />

<img width="1668" height="973" alt="image" src="https://github.com/user-attachments/assets/a3bc2bdc-d43a-431f-aba1-9c4c5dbcec88" />

<img width="1670" height="978" alt="image" src="https://github.com/user-attachments/assets/069b6322-dc51-45fb-860f-94eb33212ce6" />

## 📦 Getting Started / Setup Instructions

### Prerequisites

*   A modern web browser (Chrome, Firefox, Safari, etc.)
*   A text editor or IDE (VS Code, Sublime Text, Atom, etc.)
*   Basic knowledge of HTML, CSS, and JavaScript

### Installation

1.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2.  **No installation steps are required.** This project is a frontend application and does not require any server-side setup or package installation.

### Running Locally

1.  **Open `index.html` in your web browser.**  Simply navigate to the project directory and double-click the `index.html` file.  Alternatively, you can right-click the file and choose "Open with" followed by your preferred browser.

2.  **Explore the application.** You should now be able to browse products, add them to the cart, and navigate to the checkout and orders pages.

## 📂 Project Structure

```
├── backend/
│   └── products.json         # JSON data for products
├── data/
│   ├── cart.js               # Manages shopping cart data
│   ├── deliveryOptions.js    # Defines available delivery options
│   ├── products.js           # Manages product data and retrieval
│   └── orders.js             # Manages order data and storage
├── images/
│   ├── amazon-logo-white.png
│   ├── amazon-mobile-logo-white.png
│   ├── icons/
│   │   ├── cart-icon.png
│   │   ├── checkout-lock-icon.png
│   │   └── search-icon.png
│   └── products/             # Product images
│       └── athletic-cotton-socks-6-pairs.jpg
├── scripts/
│   ├── amazon.js             # Main script for the product listing page
│   ├── checkout.js           # Main script for the checkout page
│   ├── checkout/
│   │   ├── orderSummary.js   # Renders the order summary section
│   │   └── paymentSummary.js # Renders the payment summary section
│   └── utils/
│       └── money.js          # Utility functions for formatting currency
├── styles/
│   ├── pages/
│   │   ├── amazon.css        # Styles for the amazon page
│   │   ├── checkout/
│   │   │   ├── checkout-header.css # Styles for the checkout header
│   │   │   └── checkout.css      # Styles for the checkout page
│   │   └── orders.css        # Styles for the orders page
│   │   └── tracking.css      # Styles for the tracking page
│   └── shared/
│   │   ├── amazon-header.css # Styles for the shared amazon header
│   │   └── general.css       # General styles
├── checkout.html           # Checkout page
├── index.html              # Main landing page (Amazon homepage)
├── orders.html             # Orders page
└── tracking.html           # Tracking page
```

## 📬 Contact

If you have any questions or suggestions, feel free to contact me at [your-email@example.com](mailto:your-email@example.com).

## 💖 Thanks Message

Thank you for checking out this project! I hope it's helpful and informative. Happy coding!
