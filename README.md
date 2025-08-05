# ShoeStore E-commerce Website

A responsive, full-featured e-commerce web application built using HTML, CSS, JavaScript, and Handlebars with Node.js backend. The project includes a shopping cart, product views, checkout process, admin panel, and a flexible UI based on templates.

---

## 🛠️ Features

- Product Listings (Casuals, Formals, Sneakers, Sandals)
- Product Detail (Single View)
- Shopping Cart Integration
- Checkout & Payment Pages
- Contact Form
- Admin Panel for Product Insertion & Stock Updates
- 404 Error Handling
- Responsive Design using Bootstrap & FlexSlider
- Handlebars Templating with Partials for Reusability

---

## 📁 Project Structure

```
├── css/                # Stylesheets
├── fonts/              # Font files (FontAwesome, Glyphicons)
├── html/               # Static HTML pages
├── images/             # Product & UI images
├── js/                 # JavaScript files (cart, sliders, jQuery plugins)
├── src/                # Source code
│   ├── Templates/      # Handlebars partials and views
│   ├── db/             # Database connection files
│   └── index.js        # Main server file
├── .gitignore
├── package.json
├── README.md
└── w3layouts-License.txt
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/shoestore.git
cd shoestore
```

2. Install dependencies:

```bash
npm install
```

3. Setup environment variables:

Create a `.env` file in the `src/` directory and configure your DB credentials and port:

```env
PORT=3000
DB_HOST=localhost
DB_USER=root
DB_PASS=yourpassword
DB_NAME=shoestore
```

4. Start the server:

```bash
node src/index.js
```

---

## 📦 Dependencies

- express
- express-handlebars
- mysql
- dotenv
- body-parser
- path

---

## 📸 Screenshots

Add UI screenshots here if available.

---

## 📄 License

This project is licensed under the [W3Layouts License](./w3layouts-License.txt). Please check the license file for details regarding template usage.

---

## 👨‍💻 Author

- **Bhavish Kumar** – [@Github](https://github.com/Bhavish511)

---

## 🙏 Acknowledgements

- UI Template by [W3Layouts](https://w3layouts.com/)
- Bootstrap CSS
- FontAwesome Icons
